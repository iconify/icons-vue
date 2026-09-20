<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyp364biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wyp364biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:adco" /></template>
