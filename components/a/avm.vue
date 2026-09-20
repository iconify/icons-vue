<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au72xp_dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au72xp_dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:avm" /></template>
