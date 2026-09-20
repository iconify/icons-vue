<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/i2h9tmbip.css';
import '../../css/b/bswdohf5f.css';
import '../../css/d/dgdhsgi6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="i2h9tmbip"/><rect class="bswdohf5f"/><path class="dgdhsgi6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:align-vertical-space-between" /></template>
