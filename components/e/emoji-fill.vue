<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmx-s5blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmx-s5blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emoji-fill" /></template>
