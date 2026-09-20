<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob6w07hra.css';
import '../../css/w/webixmbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob6w07hra"/><path clip-rule="evenodd" class="webixmbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hst" /></template>
