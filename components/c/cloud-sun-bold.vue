<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7ajkhrwp.css';
import '../../css/z/zb6pr8b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7ajkhrwp"/><path class="zb6pr8b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-sun-bold" /></template>
