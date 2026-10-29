<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7o7bfbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7o7bfbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-owl-solid" /></template>
