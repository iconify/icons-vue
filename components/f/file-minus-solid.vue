<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks9pbzbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks9pbzbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-minus-solid" /></template>
