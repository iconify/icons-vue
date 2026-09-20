<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_h8hs5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_h8hs5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-6-sharp" /></template>
