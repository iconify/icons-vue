<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iobqtibmb.css';
import '../../css/m/mpwpx1vpl.css';
import '../../css/f/fk33t7eqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iobqtibmb"/><path class="mpwpx1vpl"/><path class="fk33t7eqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-database" /></template>
