<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muz_ezbtz.css';
import '../../css/w/w21ld6b4s.css';
import '../../css/k/kxk-2wido.css';
import '../../css/n/n2j8p5b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muz_ezbtz"/><path class="w21ld6b4s"/><path class="kxk-2wido"/><path class="n2j8p5b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:joomla" /></template>
