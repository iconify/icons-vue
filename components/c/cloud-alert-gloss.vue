<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm30borfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm30borfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-alert-gloss" /></template>
