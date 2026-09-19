<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbw1l3b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbw1l3b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:blades-horizontal" /></template>
