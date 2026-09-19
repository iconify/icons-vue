<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui2ki_b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ui2ki_b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:google-wallet" /></template>
