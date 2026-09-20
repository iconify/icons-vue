<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aivkf70qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aivkf70qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockerizalo-light" /></template>
