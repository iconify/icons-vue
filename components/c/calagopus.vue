<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz1otrbai.css';
import '../../css/e/eka_oeb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gz1otrbai"/><path class="eka_oeb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calagopus" /></template>
