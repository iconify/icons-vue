<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9-vwpbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9-vwpbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-japanese-yen-sharp-fill" /></template>
