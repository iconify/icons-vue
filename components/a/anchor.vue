<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9_ihwbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9_ihwbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:anchor" /></template>
