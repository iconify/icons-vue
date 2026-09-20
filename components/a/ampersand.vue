<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asfjflilj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="asfjflilj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ampersand" /></template>
