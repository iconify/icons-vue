<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxxd9_b1b.css';
import '../../css/m/m8u4nj3lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxxd9_b1b"/><path class="m8u4nj3lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:folder-plus" /></template>
