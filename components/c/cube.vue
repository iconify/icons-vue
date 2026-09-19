<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw-771bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rw-771bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:cube" /></template>
