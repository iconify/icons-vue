<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4c9kzuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4c9kzuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:collabora-online" /></template>
