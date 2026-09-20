<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am6292b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="am6292b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:forum" /></template>
