<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iclyhyb7e.css';
import '../../css/j/jnkd4081l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iclyhyb7e"/><path class="jnkd4081l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-reply-all" /></template>
