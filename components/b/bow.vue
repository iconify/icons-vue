<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb7uk-s2q.css';
import '../../css/j/jlc7xm8ek.css';
import '../../css/i/imatvgb6b.css';
import '../../css/v/vzvy3h3wk.css';
import '../../css/f/fbdus0b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb7uk-s2q"/><path class="jlc7xm8ek"/><path class="imatvgb6b"/><circle class="vzvy3h3wk"/><path class="fbdus0b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bow" /></template>
