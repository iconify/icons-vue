<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy3vt9bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy3vt9bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-off-sharp" /></template>
