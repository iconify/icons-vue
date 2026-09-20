<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/j/ji8mks.css';
import '../../css/w/wcbo4y.css';
import '../../css/c/cu0zwu.css';
import '../../css/c/ct9a5j.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';
import '../../css/s/sw-cnj-zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ji8mks"/><path class="a0m25c wcbo4y"/><path class="a0m25c cu0zwu"/><path class="a0m25c ct9a5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:account-alert-loop" /></template>
