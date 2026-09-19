<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1c0n5wpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1c0n5wpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-search-alt-2" /></template>
