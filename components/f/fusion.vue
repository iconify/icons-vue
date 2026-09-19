<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6468db5n.css';
import '../../css/z/z6yg-qblf.css';
import '../../css/v/v-u89ackx.css';
import '../../css/l/l5ibq-bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q6468db5n"/><path class="z6yg-qblf"/><path class="v-u89ackx"/><path class="l5ibq-bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fusion" /></template>
