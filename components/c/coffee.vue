<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epi81h6gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epi81h6gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:coffee" /></template>
