<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_ay6dcrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="a_ay6dcrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house" /></template>
