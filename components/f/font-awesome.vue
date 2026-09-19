<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrv2rcjel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nrv2rcjel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:font-awesome" /></template>
