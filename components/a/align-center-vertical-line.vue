<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq6avsbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq6avsbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-center-vertical-line" /></template>
