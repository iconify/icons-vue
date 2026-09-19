<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq4e_bcin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq4e_bcin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:aed" /></template>
