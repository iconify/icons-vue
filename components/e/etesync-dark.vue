<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebjj2yi8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebjj2yi8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:etesync-dark" /></template>
