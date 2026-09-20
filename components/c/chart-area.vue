<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxny0p36e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxny0p36e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-area" /></template>
