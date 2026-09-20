<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irz5s5bib.css';
import '../../css/i/i6sdoobhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irz5s5bib"/><path class="i6sdoobhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:calendar-alt" /></template>
