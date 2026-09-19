<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcr7hsbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="fcr7hsbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bucket" /></template>
