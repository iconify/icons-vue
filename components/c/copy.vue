<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvx3ap5pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvx3ap5pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:copy" /></template>
