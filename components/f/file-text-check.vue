<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii--4nbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii--4nbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-text-check" /></template>
