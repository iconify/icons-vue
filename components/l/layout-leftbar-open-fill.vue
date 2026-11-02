<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hby3n6ass.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hby3n6ass"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-leftbar-open-fill" /></template>
