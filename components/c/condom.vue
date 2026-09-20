<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za9cmqb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="za9cmqb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:condom" /></template>
