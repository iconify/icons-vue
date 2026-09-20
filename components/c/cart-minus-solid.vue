<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiw9x1boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="aiw9x1boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cart-minus-solid" /></template>
