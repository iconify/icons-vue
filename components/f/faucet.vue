<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwti5uqfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cwti5uqfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:faucet" /></template>
