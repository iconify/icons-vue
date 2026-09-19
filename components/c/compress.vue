<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li3cosb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="li3cosb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:compress" /></template>
