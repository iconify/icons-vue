<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd_9zuben.css';
import '../../css/q/q6ln7jzvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vd_9zuben"/><path class="q6ln7jzvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:close-circle-o" /></template>
