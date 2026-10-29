<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhwwc2blb.css';
import '../../css/b/bef-jeb5r.css';
import '../../css/n/nz-mu3bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhwwc2blb wm-a"/><path class="bef-jeb5r wm-k"/><path class="nz-mu3bbv wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:balloon" /></template>
