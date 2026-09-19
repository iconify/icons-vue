<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2kj08brn.css';
import '../../css/l/lidjc4bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2kj08brn"/><path class="lidjc4bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-dashed-half-filled" /></template>
