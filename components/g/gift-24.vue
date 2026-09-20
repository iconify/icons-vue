<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4nu48kyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4nu48kyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:gift-24" /></template>
