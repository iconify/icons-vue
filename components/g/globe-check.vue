<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auqntsblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auqntsblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-check" /></template>
