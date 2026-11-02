<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7hrz9bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7hrz9bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:invite-line" /></template>
