<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpoxny2nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpoxny2nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-pause" /></template>
