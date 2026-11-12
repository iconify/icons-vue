<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-zw2h7ds.css';
import '../../css/a/acmcm-bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-zw2h7ds"/><path class="acmcm-bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-tag-manager-dark" /></template>
