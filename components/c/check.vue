<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4s1fymmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4s1fymmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:check" /></template>
