<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3-4pu7qp.css';
import '../../css/l/l3r2gvztf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3-4pu7qp"/><path class="l3r2gvztf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:curator-bookmarks" /></template>
