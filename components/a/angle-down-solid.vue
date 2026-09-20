<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em4gfp9qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em4gfp9qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:angle-down-solid" /></template>
