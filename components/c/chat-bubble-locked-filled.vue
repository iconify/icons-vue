<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecwn0mb8b.css';
import '../../css/b/beq9-lbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecwn0mb8b"/><path class="beq9-lbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-bubble-locked-filled" /></template>
