<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz-2g9fdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-2g9fdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:archlinux" /></template>
