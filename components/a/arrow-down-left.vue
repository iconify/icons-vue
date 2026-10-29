<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qph67wbba.css';
import '../../css/f/fhycmcb-v.css';
import '../../css/f/fb0las6fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qph67wbba wm-shadow"/><path class="fhycmcb-v wm-k"/><path class="fb0las6fs wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:arrow-down-left" /></template>
