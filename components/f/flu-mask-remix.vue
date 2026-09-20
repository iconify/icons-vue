<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2l9m1bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2l9m1bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flu-mask-remix" /></template>
