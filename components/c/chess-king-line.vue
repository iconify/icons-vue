<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uapnf89jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uapnf89jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-king-line" /></template>
