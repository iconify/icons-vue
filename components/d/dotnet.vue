<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afa8v5bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afa8v5bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dotnet" /></template>
