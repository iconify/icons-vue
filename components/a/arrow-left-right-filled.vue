<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk7yzqbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7yzqbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-right-filled" /></template>
