<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/z8g2jgblp.css';
import '../../css/a/ac2-8hbbw.css';
import '../../css/o/oa7jysr2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z8g2jgblp"/><circle class="ac2-8hbbw"/><circle class="oa7jysr2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:divide" /></template>
