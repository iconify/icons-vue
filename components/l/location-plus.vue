<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh18tub9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh18tub9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-plus" /></template>
