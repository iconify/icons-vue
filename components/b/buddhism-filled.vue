<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbnf9-bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbnf9-bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:buddhism-filled" /></template>
