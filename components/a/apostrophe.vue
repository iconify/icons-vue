<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqow5khri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqow5khri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apostrophe" /></template>
