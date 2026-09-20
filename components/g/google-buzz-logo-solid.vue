<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsz3yfqbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bsz3yfqbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-buzz-logo-solid" /></template>
