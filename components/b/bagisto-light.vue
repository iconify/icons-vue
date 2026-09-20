<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu5s-5d2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zu5s-5d2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bagisto-light" /></template>
