<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az2jqwfwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az2jqwfwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:graphite" /></template>
