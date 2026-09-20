<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxfps32he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxfps32he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-6-line" /></template>
