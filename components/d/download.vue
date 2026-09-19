<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbtl-i_cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbtl-i_cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:download" /></template>
