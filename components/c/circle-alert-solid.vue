<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzzbtfbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzzbtfbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-alert-solid" /></template>
