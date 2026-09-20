<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc8qnphym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc8qnphym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:link-alt" /></template>
