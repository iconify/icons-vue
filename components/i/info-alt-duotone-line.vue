<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/au1n8dbha.css';
import '../../css/b/bl5u9pbem.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGbAVoR3ri"><g class="ft5dv1b6b"><path class="au1n8dbha"/><path class="bl5u9pbem"/></g></mask></defs><path mask="url(#SVGbAVoR3ri)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:info-alt-duotone-line" /></template>
