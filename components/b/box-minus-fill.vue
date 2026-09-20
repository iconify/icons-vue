<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atyzv4bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atyzv4bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-minus-fill" /></template>
