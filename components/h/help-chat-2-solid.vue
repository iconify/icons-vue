<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td4tfzdnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="td4tfzdnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:help-chat-2-solid" /></template>
