<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_5hb_i8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="g_5hb_i8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:collabtive" /></template>
