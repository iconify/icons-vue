<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn6ew33jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn6ew33jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:filter-mail" /></template>
