<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgobqvysn.css';
import '../../css/f/fzc4cyr3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgobqvysn"/><path class="fzc4cyr3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:api-outlined" /></template>
