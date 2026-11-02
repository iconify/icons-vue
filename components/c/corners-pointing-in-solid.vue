<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzqavrb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pzqavrb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:corners-pointing-in-solid" /></template>
