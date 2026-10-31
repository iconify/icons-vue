<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dki-1w-8i.css';
import '../../css/z/z159gwm8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="dki-1w-8i"/><path class="z159gwm8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:china" /></template>
