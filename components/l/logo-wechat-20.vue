<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fim5e0ajp.css';
import '../../css/a/asnejb9av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fim5e0ajp"/><path class="asnejb9av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:logo-wechat-20" /></template>
