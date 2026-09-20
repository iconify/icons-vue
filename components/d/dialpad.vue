<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzd9hfbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzd9hfbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:dialpad" /></template>
