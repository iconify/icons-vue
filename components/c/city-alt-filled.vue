<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5yu_ebut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5yu_ebut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:city-alt-filled" /></template>
