<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1vcys-oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1vcys-oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-right-gloss" /></template>
