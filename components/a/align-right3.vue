<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrnz5ebwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrnz5ebwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-right3" /></template>
