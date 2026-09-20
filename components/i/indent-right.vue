<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpcrhcb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpcrhcb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:indent-right" /></template>
