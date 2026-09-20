<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amtdspbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amtdspbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:a-b" /></template>
