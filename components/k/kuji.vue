<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3m48pb3x.css';
import '../../css/t/tcklekb-k.css';
import '../../css/f/fr78w7boo.css';
import '../../css/j/j4gjthbnr.css';
import '../../css/t/tatq48slt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3m48pb3x"/><path class="tcklekb-k"/><path class="fr78w7boo"/><path class="j4gjthbnr"/><path class="tatq48slt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kuji" /></template>
