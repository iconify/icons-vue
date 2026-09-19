<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu63akbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":188,"height":917};
const content = `<path class="gu63akbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:j" /></template>
