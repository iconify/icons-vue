<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz_4v-slc.css';
import '../../css/t/t9rd-mm-b.css';
import '../../css/a/acbfzvwzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="vz_4v-slc"/><path class="t9rd-mm-b"/><path class="acbfzvwzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:estonia" /></template>
