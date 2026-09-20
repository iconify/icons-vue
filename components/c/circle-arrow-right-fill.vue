<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0n3fkbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0n3fkbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-right-fill" /></template>
