<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaukvj20g.css';
import '../../css/b/b0-egysls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaukvj20g"/><path class="b0-egysls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-add-filled" /></template>
