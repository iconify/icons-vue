<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq08dbbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wq08dbbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:crown" /></template>
