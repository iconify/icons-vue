<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-wsh-5xy.css';
import '../../css/y/yr5lehd0q.css';
import '../../css/w/w-kkr8a6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-wsh-5xy"/><path class="yr5lehd0q"/><path class="w-kkr8a6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-forward-mail" /></template>
