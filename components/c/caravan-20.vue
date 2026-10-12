<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm_8txhtx.css';
import '../../css/p/pw6vk1b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tm_8txhtx"/><path class="pw6vk1b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caravan-20" /></template>
