<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz52sdd4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sz52sdd4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:largecircle-fill-circle" /></template>
