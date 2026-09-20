<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miej-3nwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miej-3nwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-down-right-square-fill" /></template>
