<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9x30lekw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9x30lekw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-9-line" /></template>
