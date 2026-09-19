<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnn96f57y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnn96f57y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lightning-alt-outline" /></template>
