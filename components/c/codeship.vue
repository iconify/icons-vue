<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3g-t4buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3g-t4buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codeship" /></template>
