<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9k4yjrxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9k4yjrxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:astonmartin" /></template>
