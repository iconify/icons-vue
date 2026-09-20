<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekht-vbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekht-vbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-t" /></template>
