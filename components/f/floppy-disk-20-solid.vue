<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5o_y4bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a5o_y4bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:floppy-disk-20-solid" /></template>
