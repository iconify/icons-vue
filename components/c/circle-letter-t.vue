<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij1jslgcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ij1jslgcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-t" /></template>
