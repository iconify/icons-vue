<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/som5nvb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="som5nvb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:code" /></template>
