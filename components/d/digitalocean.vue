<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dla8w8bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dla8w8bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:digitalocean" /></template>
