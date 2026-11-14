<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjr8epzkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjr8epzkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gears" /></template>
