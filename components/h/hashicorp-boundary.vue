<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhiafj-by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhiafj-by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-boundary" /></template>
