<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qypm3zu-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qypm3zu-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-right-down-solid" /></template>
