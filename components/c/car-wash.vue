<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blx8nrbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="blx8nrbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:car-wash" /></template>
