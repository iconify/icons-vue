<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quy73rill.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quy73rill"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:currency-dollar" /></template>
