<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntv6zhbei.css';
import '../../css/w/w5p1slozp.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ntv6zhbei"/><path class="w5p1slozp"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-plus-48" /></template>
