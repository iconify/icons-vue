<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7pwtboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lv7pwtboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:download-square2-filled" /></template>
