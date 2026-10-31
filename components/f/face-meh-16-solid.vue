<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw-hmtx_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rw-hmtx_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-meh-16-solid" /></template>
