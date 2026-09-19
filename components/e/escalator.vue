<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owpaclbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owpaclbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:escalator" /></template>
