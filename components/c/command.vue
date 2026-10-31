<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/a_vfb4ntm.css';
import '../../css/g/grhc7w2vk.css';
import '../../css/r/rphn1cc9p.css';
import '../../css/f/f1t-wwxme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="a_vfb4ntm wm-shadow"/><path class="grhc7w2vk wm-shadow"/><path class="rphn1cc9p"/><path class="f1t-wwxme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:command" /></template>
