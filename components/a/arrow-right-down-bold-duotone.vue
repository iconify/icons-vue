<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl1y521md.css';
import '../../css/l/lqz0ivbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zl1y521md"/><path class="lqz0ivbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-down-bold-duotone" /></template>
