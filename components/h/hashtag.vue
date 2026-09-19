<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_qe4db2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d_qe4db2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:hashtag" /></template>
