<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmu6qlb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmu6qlb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kotlin-logo" /></template>
