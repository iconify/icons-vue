<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyp46zrds.css';
import '../../css/s/s4z2tns2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zyp46zrds"/><path class="s4z2tns2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-messages-light" /></template>
