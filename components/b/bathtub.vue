<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at12u8goe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at12u8goe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bathtub" /></template>
