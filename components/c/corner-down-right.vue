<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7dm14bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7dm14bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:corner-down-right" /></template>
