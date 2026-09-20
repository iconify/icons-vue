<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdpm5sixb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdpm5sixb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-right-box-sharp" /></template>
