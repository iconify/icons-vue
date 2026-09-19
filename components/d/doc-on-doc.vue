<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-tor2b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v-tor2b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-on-doc" /></template>
