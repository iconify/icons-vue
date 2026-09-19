<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl25s0bgy.css';
import '../../css/r/r-n6f1bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl25s0bgy"/><path class="r-n6f1bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-right-square-filled" /></template>
