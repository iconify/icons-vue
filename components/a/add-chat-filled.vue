<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yroy_z5el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yroy_z5el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:add-chat-filled" /></template>
