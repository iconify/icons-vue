<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9y6vm_gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9y6vm_gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:expand" /></template>
