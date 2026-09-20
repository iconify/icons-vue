<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avw7e7kpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avw7e7kpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:humble-bundle-dark" /></template>
