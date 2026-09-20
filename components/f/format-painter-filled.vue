<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmue_db-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lmue_db-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:format-painter-filled" /></template>
