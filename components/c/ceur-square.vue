<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzcmdf5sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qzcmdf5sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ceur-square" /></template>
