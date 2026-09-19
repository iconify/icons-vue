<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbbhvubuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbbhvubuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-csv" /></template>
