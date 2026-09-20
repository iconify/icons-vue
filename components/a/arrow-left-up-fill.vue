<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8_4imbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8_4imbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-up-fill" /></template>
