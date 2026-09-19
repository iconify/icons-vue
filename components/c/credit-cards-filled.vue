<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm6q69bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm6q69bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-cards-filled" /></template>
