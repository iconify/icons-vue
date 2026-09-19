<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2k6oubdw.css';
import '../../css/k/kwq8pvbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2k6oubdw"/><path class="kwq8pvbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-right-stroke-square-filled" /></template>
