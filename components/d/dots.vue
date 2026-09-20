<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fplc9dbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fplc9dbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dots" /></template>
