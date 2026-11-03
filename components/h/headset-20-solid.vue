<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j30qxabgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j30qxabgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headset-20-solid" /></template>
