<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js69wbbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js69wbbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open" /></template>
