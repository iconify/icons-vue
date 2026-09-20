<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc8ninjpx.css';
import '../../css/e/epg14abwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nc8ninjpx"/><path class="epg14abwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:comment-ellipsis-o" /></template>
