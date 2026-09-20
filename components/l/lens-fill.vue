<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zarsxtjjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zarsxtjjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:lens-fill" /></template>
