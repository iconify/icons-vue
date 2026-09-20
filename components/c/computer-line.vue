<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex-mupy0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex-mupy0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-line" /></template>
