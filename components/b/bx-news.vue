<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ufupj8t.css';
import '../../css/b/bfqat1bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1ufupj8t"/><path class="bfqat1bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-news" /></template>
