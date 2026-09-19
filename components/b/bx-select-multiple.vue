<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoy6vkbrs.css';
import '../../css/b/bpq3sbcle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoy6vkbrs"/><path class="bpq3sbcle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-select-multiple" /></template>
