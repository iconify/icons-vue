<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi1rist4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi1rist4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cucumber" /></template>
