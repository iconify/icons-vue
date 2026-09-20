<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob3ob_h0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ob3ob_h0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-curvy-both-direction-2-solid" /></template>
