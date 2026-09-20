<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niq5zhxqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="niq5zhxqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:apx" /></template>
