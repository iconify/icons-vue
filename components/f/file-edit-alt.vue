<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da6jecb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="da6jecb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:file-edit-alt" /></template>
