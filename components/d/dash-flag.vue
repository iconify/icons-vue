<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r64efebaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r64efebaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:dash-flag" /></template>
