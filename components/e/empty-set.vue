<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss-s9gi8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ss-s9gi8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:empty-set" /></template>
