<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3yu25n4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c3yu25n4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:eject-remix" /></template>
