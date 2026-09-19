<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urhsqs_4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urhsqs_4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-alt" /></template>
