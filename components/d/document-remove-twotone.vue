<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kga6tz.css';
import '../../css/q/qa-o7h.css';
import '../../css/t/taf2xz.css';
import '../../css/v/vlmmxw.css';
import '../../css/a/ab0nvj.css';
import '../../css/f/fri20d.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kga6tz"/><path class="qa-o7h taf2xz vlmmxw"/><path class="ab0nvj qa-o7h"/><path class="fri20d qa-o7h taf2xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:document-remove-twotone" /></template>
