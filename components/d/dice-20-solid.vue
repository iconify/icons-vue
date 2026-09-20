<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze429bcme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ze429bcme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dice-20-solid" /></template>
