<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbsrd8h1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rbsrd8h1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ara-records-ansible-dark" /></template>
