<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcobhzbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="bcobhzbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:http" /></template>
