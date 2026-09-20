<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvcqgdbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvcqgdbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-x" /></template>
