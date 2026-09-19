<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrh3eckrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrh3eckrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-arch" /></template>
