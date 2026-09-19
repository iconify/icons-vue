<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xfsy1sb2g.css';
import '../../css/h/hi7t25b6s.css';
import '../../css/o/osq3z8b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xfsy1sb2g"/><path class="hi7t25b6s"/><path class="osq3z8b5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:joystick-05" /></template>
