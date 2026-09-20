<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcf2c5nxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcf2c5nxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-navbar-filled" /></template>
