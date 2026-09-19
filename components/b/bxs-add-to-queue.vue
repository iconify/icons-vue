<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9y7lbbej.css';
import '../../css/u/u45py-vnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9y7lbbej"/><path class="u45py-vnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-add-to-queue" /></template>
