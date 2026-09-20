<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw68vba5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw68vba5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dome-light" /></template>
