<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odvo0kyvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odvo0kyvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:daemon-sync-dark" /></template>
