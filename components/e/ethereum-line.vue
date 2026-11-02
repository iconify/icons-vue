<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvbb7gbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvbb7gbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ethereum-line" /></template>
