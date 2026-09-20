<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjv-31b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjv-31b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-sharp" /></template>
