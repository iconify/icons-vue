<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/p7-ogkgpo.css';
import '../../css/h/hb6jkcb9k.css';
import '../../css/p/p86qfqb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="p7-ogkgpo wm-shadow"/><path class="hb6jkcb9k wm-shadow"/><path class="p86qfqb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:arrow-down-to-line" /></template>
