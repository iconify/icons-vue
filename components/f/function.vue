<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epde73bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epde73bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:function" /></template>
