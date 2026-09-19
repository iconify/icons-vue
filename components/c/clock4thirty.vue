<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt893gged.css';
import '../../css/e/eg39dacou.css';
import '../../css/l/lorjk2lby.css';
import '../../css/f/fr-oqcc9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt893gged"/><path class="eg39dacou"/><path class="lorjk2lby"/><path class="fr-oqcc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clock4thirty" /></template>
