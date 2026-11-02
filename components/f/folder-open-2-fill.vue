<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc8qyybol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc8qyybol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-open-2-fill" /></template>
