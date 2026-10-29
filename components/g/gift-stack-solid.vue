<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-977cbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-977cbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gift-stack-solid" /></template>
