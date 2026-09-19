<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2aal61ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2aal61ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:dataproc-metastore" /></template>
