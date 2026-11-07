<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akziae8mx.css';
import '../../css/h/h3ccn7bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akziae8mx"/><path class="h3ccn7bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-bolt-bold" /></template>
