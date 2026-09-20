<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2iri-tbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2iri-tbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:document-update" /></template>
