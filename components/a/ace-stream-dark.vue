<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxv7fm38f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxv7fm38f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ace-stream-dark" /></template>
