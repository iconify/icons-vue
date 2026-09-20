<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqwjjpb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kqwjjpb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:infra" /></template>
