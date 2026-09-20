<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp8t6f6gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bp8t6f6gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:delete-keyboard-remix" /></template>
