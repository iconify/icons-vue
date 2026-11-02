<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li2usrbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li2usrbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hop-fill" /></template>
