<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uedtu89cj.css';
import '../../css/b/b2m7ke2wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uedtu89cj"/><path class="b2m7ke2wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:conversation" /></template>
