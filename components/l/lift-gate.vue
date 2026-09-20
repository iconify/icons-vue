<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osv1b-n0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="osv1b-n0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lift-gate" /></template>
