<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho_vuac_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho_vuac_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:divider-outline" /></template>
