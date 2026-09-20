<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r84escbrd.css';
import '../../css/q/qffwwpzrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r84escbrd"/><path class="qffwwpzrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:kindle-hold-bold" /></template>
