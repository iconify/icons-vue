<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja86lubud.css';
import '../../css/s/s78ya2efd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja86lubud"/><path class="s78ya2efd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:comment-alt-message" /></template>
