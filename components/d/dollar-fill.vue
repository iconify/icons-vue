<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2pb8ubfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2pb8ubfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dollar-fill" /></template>
