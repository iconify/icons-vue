<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz1l9ignk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tz1l9ignk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:add-chat-two-filled" /></template>
