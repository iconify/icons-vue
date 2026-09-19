<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w364qybrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":506,"height":614};
const content = `<path class="w364qybrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:equal" /></template>
