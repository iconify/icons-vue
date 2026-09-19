<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9gza1b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p9gza1b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:document" /></template>
