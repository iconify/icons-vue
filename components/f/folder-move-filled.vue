<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-adhfbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-adhfbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-move-filled" /></template>
