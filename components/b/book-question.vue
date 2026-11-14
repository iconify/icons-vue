<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="svnd_cw9z"/><path class="f_hix8bdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-question" /></template>
<style>
.f_hix8bdi {
  d: path("M3.5 16A2.5 2.5 0 0 1 6 13.5h7m3.5 2.5a2 2 0 1 1 2.75 1.75q-.75.5-.75 1.25");
}

.svnd_cw9z {
  d: path("M15.727 19H6q-.07.001-.14-.001q-.07-.003-.14-.009t-.139-.017t-.138-.024t-.136-.032t-.134-.04t-.132-.047t-.129-.055t-.126-.062t-.122-.068t-.118-.075t-.114-.082t-.108-.088q-.054-.046-.104-.094q-.051-.049-.099-.1q-.047-.051-.092-.105t-.087-.11t-.08-.115q-.039-.058-.074-.119t-.067-.123t-.06-.126t-.053-.13t-.045-.132t-.038-.135t-.03-.137q-.014-.069-.023-.138q-.009-.07-.015-.139q-.005-.07-.007-.14t.001-.14t.008-.14q.007-.07.017-.139T3.5 16V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T6 2.5h13v8.573");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
