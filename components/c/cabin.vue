<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk51rwbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fk51rwbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cabin" /></template>
