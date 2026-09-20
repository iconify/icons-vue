<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6nwf-u2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6nwf-u2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-up-line" /></template>
