<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw4qn3b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw4qn3b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:list-view" /></template>
