<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2_iq0bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2_iq0bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:link-bottom" /></template>
