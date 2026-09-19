<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tchv4_7zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tchv4_7zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:facemask" /></template>
