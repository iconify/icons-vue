<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/het-f1szb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="het-f1szb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:facebook-logo-1-remix" /></template>
