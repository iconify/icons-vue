<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5e5ikb2t.css';
import '../../css/w/w07hk-pry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5e5ikb2t"/><path class="w07hk-pry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:avocado" /></template>
