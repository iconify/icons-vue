<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc7qydb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oc7qydb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:entrance" /></template>
