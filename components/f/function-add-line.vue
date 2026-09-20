<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uab5gm8gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uab5gm8gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:function-add-line" /></template>
