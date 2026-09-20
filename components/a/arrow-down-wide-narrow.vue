<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpvtkxbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpvtkxbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-down-wide-narrow" /></template>
