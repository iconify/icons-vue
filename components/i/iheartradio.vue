<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z72rv3bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z72rv3bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iheartradio" /></template>
