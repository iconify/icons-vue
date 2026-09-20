<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm2bjzmsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm2bjzmsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:christmas-hat-fill" /></template>
