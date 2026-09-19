<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyaez7yho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyaez7yho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-left-sm" /></template>
