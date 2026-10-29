<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmlcut78i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmlcut78i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:container-solid" /></template>
