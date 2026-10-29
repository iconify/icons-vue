<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_-xw2btr.css';
import '../../css/n/nmu8t-fwz.css';
import '../../css/v/vdtxttb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-xw2btr wm-shadow"/><path class="nmu8t-fwz wm-k"/><path class="vdtxttb4w wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chevron-down" /></template>
