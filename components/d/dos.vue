<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3r5xob4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3r5xob4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:dos" /></template>
