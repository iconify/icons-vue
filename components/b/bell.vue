<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecobljbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecobljbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:bell" /></template>
