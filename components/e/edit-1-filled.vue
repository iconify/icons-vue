<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz9ip8bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz9ip8bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:edit-1-filled" /></template>
