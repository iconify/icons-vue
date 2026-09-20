<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ad2k74bfu.css';
import '../../css/g/gh-igyr-n.css';
import '../../css/f/f3wvhbb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="ad2k74bfu"/><path class="gh-igyr-n"/><path clip-rule="evenodd" class="f3wvhbb1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-search-fill" /></template>
