<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eos9p4b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eos9p4b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-alt-minus" /></template>
