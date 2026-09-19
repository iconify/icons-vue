<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx94i8bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bx94i8bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chat-bubble-2" /></template>
