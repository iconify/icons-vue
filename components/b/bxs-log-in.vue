<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5vi_rvrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5vi_rvrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-log-in" /></template>
