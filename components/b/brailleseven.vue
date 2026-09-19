<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy9s2_bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="vy9s2_bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailleseven" /></template>
