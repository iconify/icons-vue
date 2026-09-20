<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llh2edb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llh2edb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:euro-sharp-two-tone" /></template>
