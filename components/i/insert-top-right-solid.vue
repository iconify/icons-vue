<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prxt3uguk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="prxt3uguk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:insert-top-right-solid" /></template>
