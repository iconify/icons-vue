<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux7n9dami.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux7n9dami"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kika" /></template>
