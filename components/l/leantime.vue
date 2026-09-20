<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixt72zwcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixt72zwcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:leantime" /></template>
