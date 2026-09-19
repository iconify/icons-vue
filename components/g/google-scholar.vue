<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn1urwb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qn1urwb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:google-scholar" /></template>
