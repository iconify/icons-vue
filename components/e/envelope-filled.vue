<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpqqn6bis.css';
import '../../css/r/rln8920_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpqqn6bis"/><path class="rln8920_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:envelope-filled" /></template>
