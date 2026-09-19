<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-0z_jbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-0z_jbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:breast-pump" /></template>
