<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkpmdpl1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkpmdpl1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:arrow-right-outline" /></template>
