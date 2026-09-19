<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tin16p2kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tin16p2kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:compass-fill" /></template>
