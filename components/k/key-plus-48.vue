<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhs8peimt.css';
import '../../css/x/xuaqg0a7u.css';
import '../../css/g/gbjmahy1r.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zhs8peimt"/><path class="xuaqg0a7u"/><path class="gbjmahy1r"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-plus-48" /></template>
