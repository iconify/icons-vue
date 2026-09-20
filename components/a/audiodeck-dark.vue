<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yasmpbimd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yasmpbimd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiodeck-dark" /></template>
