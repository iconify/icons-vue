<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7a9p93tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7a9p93tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-right-24" /></template>
