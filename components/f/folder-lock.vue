<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-d65nber.css';
import '../../css/j/je17xlb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="p-d65nber"/><path class="je17xlb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:folder-lock" /></template>
