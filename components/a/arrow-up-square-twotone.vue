<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj437j.css';
import '../../css/i/iw1iew.css';
import '../../css/e/eygq0a.css';
import '../../css/y/y4wbml.css';
import '../../css/r/rp-3po.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj437j iw1iew"/><path class="eygq0a iw1iew y4wbml"/><path class="iw1iew rp-3po y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-up-square-twotone" /></template>
