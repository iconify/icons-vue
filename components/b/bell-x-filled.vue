<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xba6fzbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xba6fzbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-x-filled" /></template>
