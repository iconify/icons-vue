<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz0hucbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz0hucbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-minus" /></template>
