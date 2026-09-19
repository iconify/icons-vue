<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk-o0h0gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hk-o0h0gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowshape-turn-up-left-2-fill" /></template>
