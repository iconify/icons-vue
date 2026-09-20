<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o33ws1aqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o33ws1aqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:link-variant" /></template>
