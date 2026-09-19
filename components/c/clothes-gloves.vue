<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d48krva-u.css';
import '../../css/n/nu3w2abno.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkYqmLdhu"><g class="ft5dv1b6b"><path class="d48krva-u"/><path class="nu3w2abno"/></g></mask></defs><path mask="url(#SVGkYqmLdhu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:clothes-gloves" /></template>
