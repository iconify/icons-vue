<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5z3m501d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5z3m501d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-happy-filled" /></template>
