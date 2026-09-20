<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw6ehvpzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw6ehvpzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:chat-info" /></template>
