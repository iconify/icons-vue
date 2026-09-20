<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkww0n1py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lkww0n1py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-held-remix" /></template>
