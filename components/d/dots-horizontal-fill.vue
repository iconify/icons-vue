<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljh0thbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljh0thbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dots-horizontal-fill" /></template>
