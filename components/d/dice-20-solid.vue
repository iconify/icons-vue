<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5y2e5btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u5y2e5btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dice-20-solid" /></template>
