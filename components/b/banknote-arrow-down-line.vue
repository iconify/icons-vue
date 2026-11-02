<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzjx61b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzjx61b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:banknote-arrow-down-line" /></template>
