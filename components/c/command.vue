<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iof1jrb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iof1jrb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:command" /></template>
