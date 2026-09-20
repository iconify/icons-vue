<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myf0cab_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myf0cab_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-cancel" /></template>
