<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsuy9zbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rsuy9zbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:keycloak-wordmark" /></template>
