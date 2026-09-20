<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weim-6bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="weim-6bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dingtalk-fill" /></template>
