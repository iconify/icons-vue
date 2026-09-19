<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhxum_bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhxum_bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:help" /></template>
