<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdd_iuniy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdd_iuniy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:listmonk" /></template>
