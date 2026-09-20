<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7c9xsbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7c9xsbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bandage-filled" /></template>
