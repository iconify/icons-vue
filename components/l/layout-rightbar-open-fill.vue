<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtrxd9xag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtrxd9xag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-rightbar-open-fill" /></template>
