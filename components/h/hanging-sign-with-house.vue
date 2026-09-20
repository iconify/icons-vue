<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4puocchg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z4puocchg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hanging-sign-with-house" /></template>
