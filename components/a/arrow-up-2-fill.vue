<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzl30enaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzl30enaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-2-fill" /></template>
