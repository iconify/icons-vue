<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgf_iypbv.css';
import '../../css/s/sfsa80h7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgf_iypbv"/><path class="sfsa80h7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-locked-filled" /></template>
