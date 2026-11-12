<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irsl63llt.css';
import '../../css/n/nvwx11b3c.css';
import '../../css/n/n4xv7q49k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="irsl63llt"/><path class="nvwx11b3c"/><path class="n4xv7q49k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-portal-light" /></template>
