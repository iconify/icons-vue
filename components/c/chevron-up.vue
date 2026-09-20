<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arp62jbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="arp62jbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:chevron-up" /></template>
