<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf-uribdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf-uribdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-asia-australia" /></template>
