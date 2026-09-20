<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja69nhbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja69nhbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-remove-outline" /></template>
