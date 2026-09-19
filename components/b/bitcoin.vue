<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahus_ublf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahus_ublf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:bitcoin" /></template>
