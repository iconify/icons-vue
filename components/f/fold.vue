<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jocbzw1xx.css';
import '../../css/f/f9h36q24z.css';
import '../../css/e/ex0ms5b-c.css';
import '../../css/n/nepc0n-im.css';
import '../../css/d/doud3xbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jocbzw1xx"/><path class="f9h36q24z"/><path class="ex0ms5b-c"/><path class="nepc0n-im"/><path class="doud3xbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fold" /></template>
