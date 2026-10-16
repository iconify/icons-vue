<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-y9qh32h.css';
import '../../css/z/zcvqqxblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g-y9qh32h"/><path class="zcvqqxblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glacier-48" /></template>
