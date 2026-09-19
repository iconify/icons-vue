<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljlho-brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljlho-brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-down-left" /></template>
