<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz66p41ba.css';
import '../../css/x/xdb4trbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hz66p41ba"/><path class="xdb4trbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dafi" /></template>
