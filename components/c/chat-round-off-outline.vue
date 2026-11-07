<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j59xwccww.css';
import '../../css/h/hmxnmsbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j59xwccww"/><path class="hmxnmsbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-off-outline" /></template>
