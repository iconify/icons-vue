<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_1d1rbat.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9H518cyu"><path class="o_1d1rbat"/></mask></defs><path mask="url(#SVG9H518cyu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:book-open" /></template>
