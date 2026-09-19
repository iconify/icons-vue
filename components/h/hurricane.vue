<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8s26pbah.css';
import '../../css/s/s07htpbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8s26pbah"/><path class="s07htpbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hurricane" /></template>
