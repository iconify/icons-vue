<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a39x7accg.css';
import '../../css/w/w3pk7wb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a39x7accg"/><path class="w3pk7wb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-narrow-wide" /></template>
