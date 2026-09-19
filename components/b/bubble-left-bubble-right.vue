<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d59o-nb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d59o-nb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bubble-left-bubble-right" /></template>
