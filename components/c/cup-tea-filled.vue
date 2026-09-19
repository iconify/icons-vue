<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkk8debim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkk8debim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cup-tea-filled" /></template>
