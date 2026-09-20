<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/t/tbrf4r.css';
import '../../css/g/gsw2zd.css';
import '../../css/f/fill-from-0_3.css';
import '../../css/s/so-to-14.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c tbrf4r"/><path class="a0m25c gsw2zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:confirm-square-twotone-to-square-transition" /></template>
