<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k1k5prs-e.css';
import '../../css/j/j9n7iubvg.css';
import '../../css/v/vzvzjnbsc.css';
import '../../css/h/hunp8wb_p.css';
import '../../css/e/ef5_fibav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="k1k5prs-e"/><path class="j9n7iubvg"/><path class="vzvzjnbsc"/><path class="hunp8wb_p"/><path class="ef5_fibav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:joystick" /></template>
