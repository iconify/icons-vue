<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj437j.css';
import '../../css/i/iw1iew.css';
import '../../css/g/glst3p.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj437j iw1iew"/><path class="glst3p iw1iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-left-square-twotone" /></template>
