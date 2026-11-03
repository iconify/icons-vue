<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufe16c4_h.css';
import '../../css/c/cnog61bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ufe16c4_h"/><path class="cnog61bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dialogflow" /></template>
