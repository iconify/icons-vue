<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2jkeg0tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="p2jkeg0tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:data-filled" /></template>
