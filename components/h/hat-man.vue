<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi_9etbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zi_9etbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hat-man" /></template>
