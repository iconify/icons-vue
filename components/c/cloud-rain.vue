<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz1oid5hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz1oid5hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-rain" /></template>
