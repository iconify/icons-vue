<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntkkgxbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntkkgxbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:clapperboard-fill" /></template>
