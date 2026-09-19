<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl5jgnb6c.css';
import '../../css/z/zdmdccc7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="tl5jgnb6c"/><path class="zdmdccc7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:child" /></template>
