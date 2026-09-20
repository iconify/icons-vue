<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyuucx0_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyuucx0_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kas" /></template>
