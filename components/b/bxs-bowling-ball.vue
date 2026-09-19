<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kns1asehw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kns1asehw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bowling-ball" /></template>
