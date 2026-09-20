<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gztry8buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gztry8buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bubble-filled" /></template>
