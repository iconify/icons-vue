<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7l-2bm3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7l-2bm3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:barbell-filled" /></template>
