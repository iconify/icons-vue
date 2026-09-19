<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fbxmsfbue.css';
import '../../css/s/s3c5dhbdv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3oOjleZM"><g class="ft5dv1b6b"><rect class="fbxmsfbue"/><path class="s3c5dhbdv"/></g></mask></defs><path mask="url(#SVG3oOjleZM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:extend" /></template>
