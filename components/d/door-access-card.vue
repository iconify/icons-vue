<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r11kglm6y"/><path class="mnpc1bcki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-access-card" /></template>
<style>
.mnpc1bcki {
  d: path("M7.152 13.75q.047-.081.099-.16q.052-.078.109-.153t.118-.146q.062-.071.127-.139q.066-.067.136-.13t.143-.121t.151-.113q.077-.053.158-.102q.08-.049.164-.093q.083-.043.169-.082q.085-.038.174-.071t.178-.06t.181-.049t.184-.038t.187-.026q.093-.01.187-.014t.188-.002t.188.009t.187.021t.185.033t.182.044t.18.056t.176.066q.087.037.171.078q.084.042.166.088q.082.047.16.099q.079.051.154.108t.146.118t.139.126q.068.066.131.135q.063.07.122.143q.059.074.113.151m-6.96-1.431q.084-.12.175-.236t.186-.226q.097-.11.199-.215q.102-.106.21-.205q.108-.1.22-.193q.113-.094.231-.182q.118-.087.24-.169q.122-.081.248-.155q.127-.075.257-.143t.263-.128q.134-.061.27-.114q.137-.054.276-.1t.281-.085q.141-.038.285-.069q.143-.031.288-.055q.145-.023.291-.039q.145-.015.292-.023q.146-.008.293-.008t.293.008t.292.023t.291.039t.288.055t.285.069t.281.085t.276.1t.27.114t.263.128q.131.068.257.143t.248.156t.24.168t.231.182q.112.093.22.193M15 14h6v8h-6Zm4 4h.01");
}

.r11kglm6y {
  d: path("M12.2 20.5H3v-18h13.5v8.7M7.75 5.75h4m-2 9.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
