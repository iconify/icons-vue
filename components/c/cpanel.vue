<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9qs72-yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9qs72-yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cpanel" /></template>
