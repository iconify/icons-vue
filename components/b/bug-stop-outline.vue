<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhfe5xfqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhfe5xfqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bug-stop-outline" /></template>
