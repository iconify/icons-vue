<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpfy7f3fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpfy7f3fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flathub" /></template>
