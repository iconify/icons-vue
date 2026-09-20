<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7812fb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r7812fb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:download-list" /></template>
