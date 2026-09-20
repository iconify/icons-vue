<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzql8ab7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzql8ab7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-2-filled" /></template>
