<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw3ztwb7z.css';
import '../../css/w/wnni9vb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw3ztwb7z"/><path class="wnni9vb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:id" /></template>
