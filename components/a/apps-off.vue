<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dat_fiu7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dat_fiu7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:apps-off" /></template>
