<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5cgbab2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":614};
const content = `<path class="g5cgbab2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:keyboard" /></template>
