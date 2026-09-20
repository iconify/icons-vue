<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bve_hvb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bve_hvb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:globe-africa-solid" /></template>
