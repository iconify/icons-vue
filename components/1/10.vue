<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfqv7u9dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfqv7u9dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:10" /></template>
