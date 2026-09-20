<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdrqsdvsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdrqsdvsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-post" /></template>
