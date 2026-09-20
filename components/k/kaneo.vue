<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is05deb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="is05deb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kaneo" /></template>
