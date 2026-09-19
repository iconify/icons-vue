<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcta5_bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcta5_bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:euro-filled" /></template>
