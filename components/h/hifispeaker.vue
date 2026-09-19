<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf7_k388w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jf7_k388w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hifispeaker" /></template>
