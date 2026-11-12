<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osb188k-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="osb188k-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calibre-web-dark" /></template>
