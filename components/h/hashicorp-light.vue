<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiyq1g7qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fiyq1g7qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-light" /></template>
