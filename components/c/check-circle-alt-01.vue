<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm9476rqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rm9476rqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:check-circle-alt-01" /></template>
