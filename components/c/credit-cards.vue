<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zav3g9j2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zav3g9j2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-cards" /></template>
