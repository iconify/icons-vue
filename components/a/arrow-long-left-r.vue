<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd93lvb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jd93lvb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-left-r" /></template>
