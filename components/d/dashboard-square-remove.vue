<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9vsy49dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9vsy49dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashboard-square-remove" /></template>
