<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naq-blbtv.css';
import '../../css/l/l-0qc5b4i.css';
import '../../css/s/spe1s4bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naq-blbtv wm-k"/><path class="l-0qc5b4i wm-k"/><path class="spe1s4bal wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cloud-upload" /></template>
