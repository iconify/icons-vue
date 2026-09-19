<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh_v2e1my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh_v2e1my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:device" /></template>
