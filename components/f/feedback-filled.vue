<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9s4lmbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r9s4lmbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:feedback-filled" /></template>
