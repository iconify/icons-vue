<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzcy8-vtw.css';
import '../../css/f/fv9ax2bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzcy8-vtw"/><path class="fv9ax2bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:clock" /></template>
