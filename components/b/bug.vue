<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_w-hxjse.css';
import '../../css/w/w7drs3o1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_w-hxjse"/><path class="w7drs3o1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bug" /></template>
