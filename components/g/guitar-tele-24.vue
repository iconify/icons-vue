<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luomnfbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luomnfbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-tele-24" /></template>
