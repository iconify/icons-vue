<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygr0q7bwz.css';
import '../../css/o/opxxwacjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygr0q7bwz"/><path class="opxxwacjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chair-bold" /></template>
