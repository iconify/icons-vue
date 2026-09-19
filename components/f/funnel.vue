<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou-9p9brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ou-9p9brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:funnel" /></template>
