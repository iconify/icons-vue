<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei6n3ebmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ei6n3ebmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt-badge-a-fill" /></template>
