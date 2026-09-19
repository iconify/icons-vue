<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa96asbwu.css';
import '../../css/n/nt80sb9do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa96asbwu"/><path clip-rule="evenodd" class="nt80sb9do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:globe-solid" /></template>
