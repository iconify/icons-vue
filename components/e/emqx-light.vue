<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwad7hboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwad7hboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emqx-light" /></template>
