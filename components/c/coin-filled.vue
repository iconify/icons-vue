<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r00wx5u2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r00wx5u2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:coin-filled" /></template>
