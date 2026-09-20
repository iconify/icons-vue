<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7r3pbozs.css';
import '../../css/e/ezke5sblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7r3pbozs"/><path class="ezke5sblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lcr" /></template>
