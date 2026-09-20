<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGn8jiDgJX" x1=".5" x2=".5" y1="-1.054" y2="1.002" gradientUnits="objectBoundingBox"><stop offset="0" class="yeq-g_73z"/><stop offset=".323" class="tnwg1q5op"/><stop offset="1" class="cjsn9mc7e"/></linearGradient><linearGradient id="SVGm62vHcsh" x1="21.397" x2="21.397" y1="-1.054" y2="1.002" gradientUnits="objectBoundingBox"><stop offset="0" class="u941ctzvm"/><stop offset=".323" class="tnwg1q5op"/><stop offset="1" class="cjsn9mc7e"/></linearGradient><linearGradient id="SVGiBdLob5J" x1=".156" x2=".754" y1="-.44" y2="1.009" gradientUnits="objectBoundingBox"><stop offset="0" class="a4h2alb6k"/><stop offset=".232" class="se-t5t0fa"/><stop offset=".407" class="ehv_vsb4n"/><stop offset=".564" class="wdtv05b5t"/><stop offset=".709" class="f817go9jn"/><stop offset=".847" class="a4k9wsbxz"/><stop offset=".975" class="imb_chx8w"/><stop offset="1" class="tnwg1q5op"/></linearGradient><clipPath id="SVGseksXbjI"><path class="yheihnbxw"/></clipPath></defs><g clip-path="url(#SVGseksXbjI)"><path fill="url(#SVGn8jiDgJX)" transform="translate(-555.24 -156.938)" class="yghchkbvn"/><path fill="url(#SVGm62vHcsh)" transform="translate(-514.167 -156.938)" class="y3sks6zac"/><path fill="url(#SVGiBdLob5J)" transform="translate(-523.513 -142.84)" class="tx5eaethu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-master-co" /></template>
<style>
.a4h2alb6k {
  stop-color: var(--svg-color--fcdd98, #fcdd98);
}

.a4k9wsbxz {
  stop-color: var(--svg-color--d9a346, #d9a346);
}

.cjsn9mc7e {
  stop-color: var(--svg-color--f6db9b, #f6db9b);
}

.ehv_vsb4n {
  stop-color: var(--svg-color--f6d48b, #f6d48b);
}

.f817go9jn {
  stop-color: var(--svg-color--e6b864, #e6b864);
}

.imb_chx8w {
  stop-color: var(--svg-color--c98922, #c98922);
}

.se-t5t0fa {
  stop-color: var(--svg-color--fada94, #fada94);
}

.tnwg1q5op {
  stop-color: var(--svg-color--e6a345, #e6a345);
}

.tx5eaethu {
  d: path("M546.924 152.989a3.231 3.231 0 0 0-5.725-.035l-1.686 3.23l-1.687-3.23a3.231 3.231 0 0 0-5.725.035l-2.194 4.245c1.042-1.182 2.5-.486 3.137.717l2.366 4.356l1.21 2.315a3.2 3.2 0 0 0 1.378 1.4a3.35 3.35 0 0 0 3.026 0a3.2 3.2 0 0 0 1.378-1.4l1.21-2.315l2.366-4.356c.636-1.2 2.1-1.9 3.137-.717Z");
}

.u941ctzvm {
  stop-color: var(--svg-color--c78a28, #c78a28);
}

.wdtv05b5t {
  stop-color: var(--svg-color--efc87b, #efc87b);
}

.y3sks6zac {
  d: path("M519.451 173.456c.732-1.3 1.348-1.489 1.95-1.489c.882 0 1.494.815 1.886 1.539l1.564 3.212l-.426.7a5.836 5.836 0 0 1-7.852 2.464l-.407-.212Z");
}

.yeq-g_73z {
  stop-color: var(--svg-color--c8861c, #c8861c);
}

.yghchkbvn {
  d: path("M581.955 173.456c-.732-1.3-1.349-1.489-1.949-1.489c-.882 0-1.495.815-1.887 1.539l-1.564 3.212l.426.7a5.836 5.836 0 0 0 7.852 2.464l.407-.212Z");
}

.yheihnbxw {
  d: path("M0 0h32v32H0z");
}

</style>
