<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx0vdxm-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lx0vdxm-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-tika-binary-dark" /></template>
