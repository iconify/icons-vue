<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6mhejnyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6mhejnyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:align-middle-bold" /></template>
