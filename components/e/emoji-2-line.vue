<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbb6-l2kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbb6-l2kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emoji-2-line" /></template>
