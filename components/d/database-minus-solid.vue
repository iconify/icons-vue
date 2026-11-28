<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpmu4kbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpmu4kbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:database-minus-solid" /></template>
