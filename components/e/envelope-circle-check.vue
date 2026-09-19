<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvrx_obxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pvrx_obxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:envelope-circle-check" /></template>
