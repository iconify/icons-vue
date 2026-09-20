<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db6ndbcaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db6ndbcaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coca-cola" /></template>
