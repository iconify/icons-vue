<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9pc-2vni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="y9pc-2vni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:lastfm-rect" /></template>
