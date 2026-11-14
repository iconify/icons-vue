<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t15qqeb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chef-recommended" /></template>
<style>
.t15qqeb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14q0-.16.008-.319t.023-.318t.039-.317t.055-.314q.031-.157.07-.311q.039-.155.085-.308t.1-.303t.115-.297t.129-.292t.144-.285q.075-.141.157-.278t.17-.269q.089-.133.184-.261t.196-.252q.102-.123.209-.241t.22-.231t.231-.22t.241-.209t.252-.196t.261-.184q.132-.088.269-.17t.278-.157q.141-.076.285-.144t.292-.129t.297-.115q.15-.054.303-.1t.308-.085q.154-.039.311-.07q.156-.031.314-.055q.158-.023.317-.039q.159-.015.318-.023T10 7.5q.236 0 .471.017t.468.051t.463.085q.231.051.456.118q.226.068.447.151q.22.084.434.183q.214.1.42.214q.206.115.403.244t.384.272t.364.299q.176.157.341.325q.165.169.317.349t.29.371q.139.191.263.391q.125.2.234.409t.204.424M10 5v2.5m-7.5 9h8m7.25-2.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
