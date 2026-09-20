<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myq_jd-_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myq_jd-_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gltf" /></template>
