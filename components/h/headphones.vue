<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b70adqb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b70adqb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:headphones" /></template>
