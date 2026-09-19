<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leac04log.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leac04log"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ellevio" /></template>
