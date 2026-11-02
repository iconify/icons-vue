<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztch4hb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztch4hb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drizzle-line" /></template>
