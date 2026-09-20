<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9abeccjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9abeccjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emoncms-light" /></template>
