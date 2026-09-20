<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eub1h9d7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eub1h9d7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-scan-fill" /></template>
