<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhxm6xbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhxm6xbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-up-c" /></template>
