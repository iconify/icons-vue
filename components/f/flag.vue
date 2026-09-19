<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpx2wv53c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gpx2wv53c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flag" /></template>
