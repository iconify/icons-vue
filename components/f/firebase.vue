<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baw3zzbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baw3zzbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:firebase" /></template>
