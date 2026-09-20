<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2yj7pbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2yj7pbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bing" /></template>
