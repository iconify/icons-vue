<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8bo3ne0r.css';
import '../../css/a/a_gu8acsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8bo3ne0r"/><path class="a_gu8acsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:hd-filled" /></template>
