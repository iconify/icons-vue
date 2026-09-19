<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1wyy2ehi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1wyy2ehi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:elipsis-h" /></template>
