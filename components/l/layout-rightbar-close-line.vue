<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mihv603ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mihv603ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-rightbar-close-line" /></template>
