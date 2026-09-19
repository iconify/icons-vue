<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbw-gabhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbw-gabhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-big-down-filled" /></template>
