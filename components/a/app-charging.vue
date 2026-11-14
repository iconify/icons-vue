<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/ji5eo813c.css';
import '../../css/n/nkjssnbsa.css';
import '../../css/t/t46b2zber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ji5eo813c"/><path class="nkjssnbsa"/><path class="t46b2zber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:app-charging" /></template>
