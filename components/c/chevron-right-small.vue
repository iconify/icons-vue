<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evin8v9-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="evin8v9-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-right-small" /></template>
