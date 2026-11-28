<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmisrrbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmisrrbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:close-circle-solid" /></template>
