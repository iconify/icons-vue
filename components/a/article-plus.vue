<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs85jub3t.css';
import '../../css/x/xs84k4bav.css';
import '../../css/n/n-c0l9fka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs85jub3t"/><path clip-rule="evenodd" class="xs84k4bav"/><path class="n-c0l9fka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-plus" /></template>
