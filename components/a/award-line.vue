<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq6no00vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq6no00vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:award-line" /></template>
