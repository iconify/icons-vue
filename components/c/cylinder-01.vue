<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1xtxw5-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1xtxw5-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cylinder-01" /></template>
