<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwk2m_bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lwk2m_bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-asia-australia-20-solid" /></template>
