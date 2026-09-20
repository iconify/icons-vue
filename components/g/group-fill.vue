<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0sch-y5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0sch-y5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-fill" /></template>
