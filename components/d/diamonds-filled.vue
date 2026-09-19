<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq-8wibaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq-8wibaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:diamonds-filled" /></template>
