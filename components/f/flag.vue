<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc-i_7bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc-i_7bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:flag" /></template>
