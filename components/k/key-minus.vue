<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b516c6bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b516c6bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:key-minus" /></template>
