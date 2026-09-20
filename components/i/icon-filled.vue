<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjmdt3wxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjmdt3wxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:icon-filled" /></template>
