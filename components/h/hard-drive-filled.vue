<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czys4v05x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czys4v05x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:hard-drive-filled" /></template>
