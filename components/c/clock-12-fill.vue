<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-xkv2b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-xkv2b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-12-fill" /></template>
