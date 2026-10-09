<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip4n_nb-a.css';
import '../../css/n/nwb7bcc2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ip4n_nb-a"/><path class="nwb7bcc2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-label-48" /></template>
