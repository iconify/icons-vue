<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5_61zblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="a5_61zblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chat-bubble" /></template>
