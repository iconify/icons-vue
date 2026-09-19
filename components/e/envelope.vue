<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al1p1acvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="al1p1acvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:envelope" /></template>
