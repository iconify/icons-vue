<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7c--tbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7c--tbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:duco-auto" /></template>
