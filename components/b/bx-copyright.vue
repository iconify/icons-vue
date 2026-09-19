<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0h_kbs6z.css';
import '../../css/i/i10epfbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0h_kbs6z"/><path class="i10epfbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-copyright" /></template>
