<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oct_aobqd.css';
import '../../css/i/i-8vw9hdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="oct_aobqd"/><path class="i-8vw9hdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atlas-network-light" /></template>
