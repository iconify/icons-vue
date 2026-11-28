<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4gxjhk3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z4gxjhk3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heart-duotone" /></template>
