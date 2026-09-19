<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhhkppb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uhhkppb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-left-square" /></template>
