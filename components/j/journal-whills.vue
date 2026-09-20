<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg_kcdcxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qg_kcdcxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:journal-whills" /></template>
