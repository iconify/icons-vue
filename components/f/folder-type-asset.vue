<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="co2thn9jw"/><rect class="xn4wnzc1t"/><path class="jkszsnjdk"/><path class="ea6_fxlwq"/><path class="qj--nv27t"/><circle class="nd5umwb0m"/><circle class="qfl4ri8qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-asset" /></template>
<style>
.co2thn9jw {
  fill: var(--svg-color--ba5656, #ba5656);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.ea6_fxlwq {
  fill: var(--svg-color--414141, #414141);
  d: path("M13.937 13.325h13.126a.61.61 0 0 1 .612.612v13.126a.613.613 0 0 1-.613.613H13.938a.613.613 0 0 1-.613-.613V13.937a.61.61 0 0 1 .612-.612");
}

.jkszsnjdk {
  fill: var(--svg-color--c2c2c2, #c2c2c2);
  d: path("M13.937 11.925h13.125a2.013 2.013 0 0 1 2.013 2.013v13.125a2.01 2.01 0 0 1-2.012 2.012H13.937a2.013 2.013 0 0 1-2.013-2.013V13.938a2.013 2.013 0 0 1 2.013-2.013");
}

.nd5umwb0m {
  cx: 20.5px;
  cy: 20.5px;
  r: 2.822px;
  fill: var(--svg-color--414141, #414141);
}

.qfl4ri8qe {
  cx: 20.5px;
  cy: 20.5px;
  r: 1.121px;
  fill: var(--svg-color--c2c2c2, #c2c2c2);
}

.qj--nv27t {
  fill: var(--svg-color--c2c2c2, #c2c2c2);
  d: path("M25.754 21.2h-1.1a4.2 4.2 0 0 1-.741 1.769l.78.78a.7.7 0 1 1-.99.99l-.786-.786a4.2 4.2 0 0 1-1.761.712v1.129a.7.7 0 0 1-1.4 0v-1.141a4.2 4.2 0 0 1-1.728-.735l-.82.82a.7.7 0 1 1-.99-.99l.826-.826a4.2 4.2 0 0 1-.707-1.723h-1.171a.7.7 0 1 1 0-1.4h1.174a4.2 4.2 0 0 1 .707-1.722l-.826-.826a.7.7 0 1 1 .99-.99l.819.82a4.2 4.2 0 0 1 1.729-.735v-1.14a.7.7 0 0 1 1.4 0v1.129a4.2 4.2 0 0 1 1.762.713l.786-.787a.7.7 0 0 1 .99.99l-.781.781a4.2 4.2 0 0 1 .741 1.768h1.1a.7.7 0 0 1 0 1.4Z");
}

.xn4wnzc1t {
  width: 21px;
  height: 21px;
  x: 10px;
  y: 10px;
  fill: var(--svg-color--414141, #414141);
  rx: 2.761px;
  ry: 2.761px;
}

</style>
