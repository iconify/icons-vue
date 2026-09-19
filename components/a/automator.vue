<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gajh3do4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":474,"height":512};
const content = `<path class="gajh3do4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:automator" /></template>
