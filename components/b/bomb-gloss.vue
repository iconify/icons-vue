<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng2aok_2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2aok_2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bomb-gloss" /></template>
