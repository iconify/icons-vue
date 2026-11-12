<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it-qx-x1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="it-qx-x1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:db-ui-light" /></template>
