<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x6s3-gesu.css';
import '../../css/h/h7n74xhqs.css';
import '../../css/t/tcsfno7wt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5A3x2kwa"><g class="ft5dv1b6b"><path class="x6s3-gesu"/><path class="h7n74xhqs"/><path clip-rule="evenodd" class="tcsfno7wt"/></g></mask></defs><path mask="url(#SVG5A3x2kwa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:help" /></template>
