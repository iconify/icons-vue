<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx0qcbuxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="kx0qcbuxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:haml" /></template>
