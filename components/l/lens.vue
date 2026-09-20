<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhxeh_quw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhxeh_quw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lens" /></template>
