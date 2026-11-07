<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcq9v-bih.css';
import '../../css/d/d-wa8wj9d.css';
import '../../css/z/zvnq9o5sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcq9v-bih"/><path class="d-wa8wj9d"/><path class="zvnq9o5sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-off-bold-duotone" /></template>
