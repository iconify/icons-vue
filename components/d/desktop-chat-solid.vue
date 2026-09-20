<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no--e8__i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="no--e8__i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-chat-solid" /></template>
