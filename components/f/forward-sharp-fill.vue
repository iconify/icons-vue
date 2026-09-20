<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9z7u7b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9z7u7b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:forward-sharp-fill" /></template>
