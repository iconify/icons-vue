<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qewfvq9oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qewfvq9oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-minus" /></template>
