<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi704w7_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi704w7_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:image" /></template>
