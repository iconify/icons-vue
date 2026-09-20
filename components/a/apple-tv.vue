<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp8-wqkvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp8-wqkvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apple-tv" /></template>
