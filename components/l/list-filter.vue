<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge-qb6k6s.css';
import '../../css/l/lz4sajp4x.css';
import '../../css/o/osghi4b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge-qb6k6s"/><path class="lz4sajp4x"/><path class="osghi4b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:list-filter" /></template>
