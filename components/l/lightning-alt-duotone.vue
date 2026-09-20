<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bwtpat1un.css';
import '../../css/v/vo7nxtf0p.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGICIZJcBJ"><g class="ft5dv1b6b"><path class="bwtpat1un"/><path class="vo7nxtf0p"/></g></mask></defs><path mask="url(#SVGICIZJcBJ)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lightning-alt-duotone" /></template>
