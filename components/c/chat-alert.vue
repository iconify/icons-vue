<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/h/hmd6rr.css';
import '../../css/p/pfsmgv.css';
import '../../css/z/zahr3u.css';
import '../../css/s/so-from-70.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hmd6rr"/><path class="a0m25c pfsmgv"/><path class="a0m25c zahr3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chat-alert" /></template>
