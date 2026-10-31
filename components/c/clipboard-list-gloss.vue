<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpzidnbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpzidnbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-list-gloss" /></template>
