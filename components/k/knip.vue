<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl-rk3sls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl-rk3sls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:knip" /></template>
