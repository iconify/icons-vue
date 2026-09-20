<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drnfbnbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-7};
const content = `<path class="drnfbnbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-up-left" /></template>
