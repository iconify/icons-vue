<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx7ql7bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx7ql7bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eul" /></template>
