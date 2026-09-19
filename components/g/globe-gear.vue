<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbza77bui.css';
import '../../css/t/tu6holb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="kbza77bui"/><path class="tu6holb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-gear" /></template>
