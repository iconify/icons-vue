<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw3q38kms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw3q38kms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-news" /></template>
