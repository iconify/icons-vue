<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s82nsqbkr.css';
import '../../css/g/gn9pzlw4w.css';
import '../../css/z/z_4ii68mz.css';
import '../../css/p/pkpf1mbaa.css';
import '../../css/t/tlrj09b8v.css';
import '../../css/v/v8-zj0oev.css';
import '../../css/g/g3mawwmhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s82nsqbkr"/><circle class="gn9pzlw4w"/><circle class="z_4ii68mz"/><path class="pkpf1mbaa"/><circle class="tlrj09b8v"/><circle class="v8-zj0oev"/><path class="g3mawwmhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-tone-analyzer" /></template>
