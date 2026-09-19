<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if_6tkb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":720,"height":840};
const content = `<path class="if_6tkb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:layers" /></template>
