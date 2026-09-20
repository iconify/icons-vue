<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/net5hhbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="net5hhbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:2fas" /></template>
