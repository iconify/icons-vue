<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4qxjab_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4qxjab_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:diagonal-line-arrow-2-remix" /></template>
