<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eatr3hojb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eatr3hojb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cylinder" /></template>
