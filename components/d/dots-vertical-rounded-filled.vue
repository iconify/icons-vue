<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9uefn24g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9uefn24g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dots-vertical-rounded-filled" /></template>
