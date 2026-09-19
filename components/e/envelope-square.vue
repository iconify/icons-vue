<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4ko08bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="c4ko08bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:envelope-square" /></template>
