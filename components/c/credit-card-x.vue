<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqvbzxbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqvbzxbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-x" /></template>
