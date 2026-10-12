<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4q3a5btx.css';
import '../../css/x/x38o7w6oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d4q3a5btx"/><path class="x38o7w6oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-pdf-stroke-20" /></template>
