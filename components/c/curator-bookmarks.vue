<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3-4pu7qp.css';
import '../../css/m/mkmxqcb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3-4pu7qp"/><path class="mkmxqcb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:curator-bookmarks" /></template>
