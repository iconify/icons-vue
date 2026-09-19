<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c13o2wbqp.css';
import '../../css/t/tnle1tu0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c13o2wbqp"/><path class="tnle1tu0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:luau" /></template>
