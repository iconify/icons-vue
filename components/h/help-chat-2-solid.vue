<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk-ovoqmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kk-ovoqmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:help-chat-2-solid" /></template>
