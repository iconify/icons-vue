<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obg7u3o0l.css';
import '../../css/d/dcthf7bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":160,"height":160};
const content = `<g class="obg7u3o0l"><rect transform="matrix(.87303 .48767 -.49721 .86763 43.48 67.304)" class="dcthf7bbi"/><rect transform="matrix(.87303 .48767 -.49721 .86763 76.94 46.534)" class="dcthf7bbi"/><rect transform="matrix(.87303 .48767 -.49721 .86763 128.424 46.535)" class="dcthf7bbi"/><rect transform="matrix(.87303 .48767 -.49721 .86763 94.957 67.304)" class="dcthf7bbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:drizzle-orm-light" /></template>
