<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krkapmb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="krkapmb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:help-chat-1-solid" /></template>
