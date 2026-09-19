<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npvpxe_he.css';
import '../../css/e/e7idfvbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npvpxe_he"/><path class="e7idfvbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-react" /></template>
