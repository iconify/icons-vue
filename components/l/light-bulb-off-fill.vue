<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0qyk6byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0qyk6byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:light-bulb-off-fill" /></template>
