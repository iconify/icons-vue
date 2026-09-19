<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0jzxob9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0jzxob9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-down-right" /></template>
