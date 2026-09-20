<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6wia9bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6wia9bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:hash" /></template>
