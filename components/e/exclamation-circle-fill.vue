<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unzlyb_8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unzlyb_8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:exclamation-circle-fill" /></template>
