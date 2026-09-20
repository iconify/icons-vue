<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naiulyjpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naiulyjpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:airplane-fill" /></template>
