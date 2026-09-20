<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyp46zrds.css';
import '../../css/s/sor599b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zyp46zrds"/><path class="sor599b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-messages-light" /></template>
