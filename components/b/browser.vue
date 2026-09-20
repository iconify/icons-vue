<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc21hcbgh.css';
import '../../css/g/gis2ovb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc21hcbgh"/><path clip-rule="evenodd" class="gis2ovb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:browser" /></template>
