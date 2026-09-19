<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehi9-muav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="ehi9-muav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:circle-outline" /></template>
