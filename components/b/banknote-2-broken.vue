<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n54zvri0c.css';
import '../../css/c/c5vk6tgit.css';
import '../../css/n/na52euwwy.css';
import '../../css/k/kkrotxg9c.css';
import '../../css/a/aekpxvtae.css';
import '../../css/y/ynw34cc0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n54zvri0c"/><path class="c5vk6tgit"/><path class="na52euwwy"/><path class="kkrotxg9c"/><path class="aekpxvtae"/><path class="ynw34cc0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-2-broken" /></template>
