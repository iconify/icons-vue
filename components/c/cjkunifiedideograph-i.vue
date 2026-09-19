<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j50aadc2n.css';
import '../../css/z/z_4hbabey.css';
import '../../css/v/vg1cj4zfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j50aadc2n"/><path class="z_4hbabey"/><path class="vg1cj4zfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cjkunifiedideograph-i" /></template>
