<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-bkl50fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-bkl50fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:home-alert" /></template>
