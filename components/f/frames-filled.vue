<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5vn8bclx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="o5vn8bclx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:frames-filled" /></template>
