<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1czvcbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1czvcbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:circle-filled" /></template>
