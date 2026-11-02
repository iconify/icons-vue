<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce18o7bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce18o7bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brightness-line" /></template>
