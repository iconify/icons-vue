<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei6395-9p.css';
import '../../css/e/ekf9xwedv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei6395-9p"/><path class="ekf9xwedv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:globe-timezone-light" /></template>
