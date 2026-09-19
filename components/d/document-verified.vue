<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gigp-2bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gigp-2bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-verified" /></template>
