<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqrj7tboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqrj7tboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:app-window-frown-solid" /></template>
