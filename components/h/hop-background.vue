<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGgp4kDeCZ)" class="r4i437pya"/><path clip-rule="evenodd" class="mrgw-nbnh"/></g><defs><linearGradient id="SVGgp4kDeCZ" x1="17.514" x2="6.843" y1="6.18" y2="18.183" gradientUnits="userSpaceOnUse"><stop class="ce3mtpr9y"/><stop offset="1" class="j9z38lb5y"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hop-background" /></template>
<style>
.ce3mtpr9y {
  stop-color: var(--svg-color--e995a5, #e995a5);
}

.ft5dv1b6b {
  fill: none;
}

.j9z38lb5y {
  stop-color: var(--svg-color--be42ed, #be42ed);
}

.mrgw-nbnh {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.37 4.402L19.715 9.3a1.6 1.6 0 0 1 .155 1.549c-.15.35-.47.6-.835.687c-.389.092-.725-.04-1.074-.179l-.162-.063h-.005v.005c.37.63.686 1.292.944 1.977c.124.327-.03.71-.358.828a.61.61 0 0 1-.743-.28s-1.214-2.009-2.193-2.95c-.87-.839-1.817-1.57-2.862-2.088a9.3 9.3 0 0 0-3.315-.914c-1.147-.102-2.314-.008-3.49.189c-.553.092-1.11-.236-1.252-.782c-.155-.59.157-1.093.768-1.324h.006c5.513-1.867 10.154 1.619 10.497 1.876l.004.003h.002l.002-.001v-.004c-.755-1.104-1.07-2.004-1.106-2.854c-.039-.933 1.149-1.34 1.674-.573M7.648 19.6l-3.362-4.925a1.6 1.6 0 0 1-.154-1.547a1.2 1.2 0 0 1 .834-.686c.388-.092.725.042 1.075.18l.161.063h.002l.002-.002l.001-.002a13 13 0 0 1-.942-1.972c-.12-.32.014-.692.327-.825a.61.61 0 0 1 .772.27s1.215 2.008 2.193 2.95c.87.838 1.817 1.57 2.862 2.087a9.3 9.3 0 0 0 3.315.914c1.148.102 2.314.01 3.49-.189c.553-.093 1.11.235 1.252.781c.153.591-.157 1.093-.768 1.323h-.006c-5.506 1.866-10.146-1.612-10.496-1.875l-.005-.003q-.006-.001-.004.005c.759 1.11 1.074 2.013 1.107 2.868c.035.933-1.13 1.355-1.656.585");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
