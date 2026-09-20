<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0ibx6bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0ibx6bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dodo" /></template>
