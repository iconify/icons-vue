<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osedktbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="osedktbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:five" /></template>
