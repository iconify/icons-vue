<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn52d-b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn52d-b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alphabet-thai" /></template>
