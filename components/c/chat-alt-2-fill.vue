<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxvw3pbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uxvw3pbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-2-fill" /></template>
