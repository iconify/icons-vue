<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6rzbfbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6rzbfbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-left-02" /></template>
