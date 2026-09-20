<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/s/s6fvfe.css';
import '../../css/n/n84zbz.css';
import '../../css/f/fill-from-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c s6fvfe"/><path class="a0m25c n84zbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:circle-twotone-to-confirm-circle-transition" /></template>
