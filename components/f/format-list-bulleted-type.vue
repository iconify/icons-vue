<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1bsn1l_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1bsn1l_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-list-bulleted-type" /></template>
