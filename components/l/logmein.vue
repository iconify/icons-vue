<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3hs09rgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3hs09rgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:logmein" /></template>
