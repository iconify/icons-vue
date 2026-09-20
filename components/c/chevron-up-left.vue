<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0kq4zbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0kq4zbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chevron-up-left" /></template>
