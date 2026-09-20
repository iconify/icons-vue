<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb3qrybmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb3qrybmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:diamond-filled" /></template>
