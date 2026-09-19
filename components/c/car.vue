<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsfq8unvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsfq8unvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:car" /></template>
