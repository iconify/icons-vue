<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0a-z351k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0a-z351k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keycloak-light" /></template>
