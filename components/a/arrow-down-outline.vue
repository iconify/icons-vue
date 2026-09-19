<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bizf7qbor.css';
import '../../css/h/heochxbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bizf7qbor"/><path clip-rule="evenodd" class="heochxbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:arrow-down-outline" /></template>
