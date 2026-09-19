<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbq9c8hyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="tbq9c8hyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bicycle" /></template>
