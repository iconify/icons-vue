<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss7jp2b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7jp2b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-dots-3-filled" /></template>
