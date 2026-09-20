<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_14z8ekf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_14z8ekf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-japanese-yen" /></template>
