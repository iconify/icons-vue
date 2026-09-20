<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwzdfkbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwzdfkbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down" /></template>
