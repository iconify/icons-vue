<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6fk_ut1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":392};
const content = `<path class="o6fk_ut1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:favorite" /></template>
