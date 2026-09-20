<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaw5a66hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaw5a66hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-down-linear" /></template>
