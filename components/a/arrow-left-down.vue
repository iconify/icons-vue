<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plzcpyf-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plzcpyf-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left-down" /></template>
