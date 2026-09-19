<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rx1fmmb4e.css';
import '../../css/e/e6ug7etno.css';
import '../../css/v/v98sb2usu.css';
import '../../css/b/bomlk53dk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAIc3Obvc"><g class="ft5dv1b6b"><path class="rx1fmmb4e"/><rect class="e6ug7etno"/><rect transform="rotate(90 13 18)" class="v98sb2usu"/><rect transform="rotate(90 13 25)" class="bomlk53dk"/></g></mask></defs><path mask="url(#SVGAIc3Obvc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:iwatch-two" /></template>
