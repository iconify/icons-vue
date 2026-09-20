<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/r/rs9o5v.css';
import '../../css/r/rje0ii.css';
import '../../css/y/y4wbml.css';
import '../../css/u/ul_dtz.css';
import '../../css/e/e7acus.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew rs9o5v"/><path class="iw1iew rje0ii y4wbml"/><path class="iw1iew ul_dtz y4wbml"/><path class="e7acus iw1iew y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:emoji-smile-twotone" /></template>
