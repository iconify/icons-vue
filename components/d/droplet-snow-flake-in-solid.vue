<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcsqp3bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcsqp3bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:droplet-snow-flake-in-solid" /></template>
