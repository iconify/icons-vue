<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr9tc44vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fr9tc44vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x2-16-solid" /></template>
