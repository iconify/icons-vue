<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rop--mbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rop--mbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:channel" /></template>
