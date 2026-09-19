<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqt5a61jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b eqt5a61jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:compare" /></template>
