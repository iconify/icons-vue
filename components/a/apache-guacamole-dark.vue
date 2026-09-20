<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0ql_sbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h0ql_sbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-guacamole-dark" /></template>
