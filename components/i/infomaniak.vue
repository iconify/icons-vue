<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj8zdqb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj8zdqb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:infomaniak" /></template>
