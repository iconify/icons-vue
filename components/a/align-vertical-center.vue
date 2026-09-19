<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orcu2zbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orcu2zbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-vertical-center" /></template>
