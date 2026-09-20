<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4ajofb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="y4ajofb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chevron-right-circle" /></template>
