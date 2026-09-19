<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c98at3bul.css';
import '../../css/z/z4-r-ybfy.css';
import '../../css/t/t6wz8cb3t.css';
import '../../css/w/wifws7q6t.css';
import '../../css/r/rj9730bre.css';
import '../../css/z/z9r-fmfog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c98at3bul"/><circle class="z4-r-ybfy"/><circle class="t6wz8cb3t"/><circle class="wifws7q6t"/><circle class="rj9730bre"/><circle class="z9r-fmfog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dice-5" /></template>
