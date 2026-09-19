<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp2apd1jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp2apd1jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:bus" /></template>
