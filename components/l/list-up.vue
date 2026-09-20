<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weoy5sb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="weoy5sb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-up" /></template>
