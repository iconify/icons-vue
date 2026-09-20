<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgteduhvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pgteduhvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fast-forward" /></template>
