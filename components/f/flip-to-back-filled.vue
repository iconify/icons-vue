<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m363_p6yk.css';
import '../../css/q/q9ju5jb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m363_p6yk"/><path class="q9ju5jb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flip-to-back-filled" /></template>
