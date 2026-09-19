<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o05od65xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o05od65xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:clipboard-outline" /></template>
