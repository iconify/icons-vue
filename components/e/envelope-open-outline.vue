<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1gf3kb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1gf3kb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:envelope-open-outline" /></template>
