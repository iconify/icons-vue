<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvfn_ybno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvfn_ybno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:assignment-error-filled" /></template>
