<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7nz9-bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k7nz9-bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hotpot" /></template>
