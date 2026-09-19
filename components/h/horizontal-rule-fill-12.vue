<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_3bmbf_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a_3bmbf_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:horizontal-rule-fill-12" /></template>
