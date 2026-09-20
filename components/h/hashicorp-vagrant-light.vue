<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbw96sg2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbw96sg2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-vagrant-light" /></template>
