<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0c3qtbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="c0c3qtbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bug-1" /></template>
