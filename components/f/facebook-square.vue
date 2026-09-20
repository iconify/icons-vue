<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmj1afbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmj1afbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:facebook-square" /></template>
