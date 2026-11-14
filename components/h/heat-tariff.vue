<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mytjudn9c"/><path class="z-q75lb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-tariff" /></template>
<style>
.mytjudn9c {
  d: path("M13.012 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h6.5l6 6v3.215");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-q75lb4p {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-7.806 8.416q-.18.141-.381.25t-.417.184t-.442.112q-.225.038-.454.038q-.135 0-.27-.013q-.134-.013-.266-.04q-.133-.026-.262-.065q-.13-.04-.254-.091q-.125-.052-.244-.116q-.119-.063-.232-.138q-.112-.076-.217-.161q-.104-.086-.2-.181q-.095-.096-.181-.2t-.161-.217t-.138-.232t-.116-.244q-.051-.124-.091-.254q-.039-.129-.065-.262q-.027-.132-.04-.266q-.013-.135-.013-.27c0-1.75.5-2.75 1.5-3.5c0 1 .5 1.75 1.25 2c-.25-1.75-.5-3.5 0-5.25c1.286 1.143 2.001 2.368 2.377 3.675M14.5 14.5H19l3 3l-4.5 4.5l-3-3Z");
}

</style>
