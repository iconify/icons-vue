<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx7kf_b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vx7kf_b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-powerpoint" /></template>
