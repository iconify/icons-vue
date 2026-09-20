<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-d3ovb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-d3ovb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-terraform-dark" /></template>
