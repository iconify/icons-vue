<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w8itr8l-v.css';
import '../../css/l/lw94e4bci.css';
import '../../css/p/pwm960b_x.css';
import '../../css/o/o6nqylbgn.css';
import '../../css/k/krqvq8bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w8itr8l-v wm-k"/><path class="lw94e4bci wm-k"/><path class="pwm960b_x wm-k"/><path class="o6nqylbgn wm-shine"/><path class="krqvq8bsd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:badge-percent" /></template>
