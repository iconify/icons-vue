<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey_qkc5et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey_qkc5et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:language" /></template>
