<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e01i893uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e01i893uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:facebook" /></template>
