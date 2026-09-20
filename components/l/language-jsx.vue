<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr256sbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr256sbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-jsx" /></template>
