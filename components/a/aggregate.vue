<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe8pdjbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe8pdjbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:aggregate" /></template>
