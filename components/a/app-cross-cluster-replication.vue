<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb78y2rwy.css';
import '../../css/t/tm8w-yurb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hb78y2rwy"/><path class="ouiIcon__fillSecondary tm8w-yurb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-cross-cluster-replication" /></template>
