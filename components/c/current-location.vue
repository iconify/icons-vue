<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp8fatbpd.css';
import '../../css/d/dlc29abjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="gp8fatbpd"/><path class="dlc29abjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:current-location" /></template>
