<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egs57ly1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egs57ly1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:customize" /></template>
