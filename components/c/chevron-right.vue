<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqmqmju1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oqmqmju1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chevron-right" /></template>
