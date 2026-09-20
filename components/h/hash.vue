<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p70ahyblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p70ahyblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:hash" /></template>
