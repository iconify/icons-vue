<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ara_cab0k.css';
import '../../css/o/o6es3ib2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ara_cab0k"/><path class="o6es3ib2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-off-48-bold" /></template>
