<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcq99_yio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcq99_yio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:battery-charging-fill" /></template>
