<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za6tz-qdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za6tz-qdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:glass-filled" /></template>
