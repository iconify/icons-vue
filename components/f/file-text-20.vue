<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-g74icta.css';
import '../../css/s/sjzg4vb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="sjzg4vb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-text-20" /></template>
