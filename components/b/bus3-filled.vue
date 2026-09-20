<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szxt5sb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szxt5sb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bus3-filled" /></template>
