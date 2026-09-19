<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvng27k2m.css';
import '../../css/u/utmbef4et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<rect class="cvng27k2m"/><rect class="utmbef4et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:answer-bot-26" /></template>
