<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><filter id="SVGb2jxBcic" width="1.07" height="1.09" x="-.03" y="-.03"><feOffset dy="2" in="SourceAlpha"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="SourceAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 .3 0"/></filter><filter id="SVGIvo0AyAL" width="1.05" height="1.08" x="-.02" y="-.04"><feGaussianBlur in="SourceAlpha" result="b" stdDeviation=".5"/><feOffset dy="2"/><feComposite in2="SourceAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix result="m" values="0 0 0 0 1 0 0 0 0 .805 0 0 0 0 .249 0 0 0 1 0"/><feOffset dy="-2" in="b"/><feComposite in2="SourceAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 .4 0"/><feMerge><feMergeNode in="m"/><feMergeNode/></feMerge></filter><filter id="SVG4GE1BbiY" width="1.05" height="1.06" x="-.03" y="-.03"><feOffset dy="1" in="SourceAlpha"/><feGaussianBlur stdDeviation="1"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 .4 0"/></filter><linearGradient id="SVGvu9FgdJy" x1="11" x2="117" y1="11" y2="117" gradientUnits="userSpaceOnUse"><stop offset="0" class="n3082_b6w"/><stop offset="1" class="r569shb7i"/></linearGradient><linearGradient id="SVGDBe48c8R" x1="18" x2="110" y1="18" y2="110" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="gfy_s4b2q"/></linearGradient><path id="SVG2PrXJeOk" class="agy9f0mgq"/><path id="SVGfKgmLdtu" class="do4dhqbxt"/></defs><g class="bi12bsetm"><g transform="translate(.55 .4)scale(.24138)"><use filter="url(#SVGb2jxBcic)" href="#SVG2PrXJeOk" class="ivjvz2eii"/><use fill="url(#SVGvu9FgdJy)" href="#SVG2PrXJeOk"/><use filter="url(#SVGIvo0AyAL)" href="#SVG2PrXJeOk" class="ivjvz2eii"/><path class="k5h5b149g"/><use filter="url(#SVG4GE1BbiY)" href="#SVGfKgmLdtu" class="ivjvz2eii"/><use fill="url(#SVGDBe48c8R)" href="#SVGfKgmLdtu"/></g><path class="as_ysvb9k"/><path class="y4cbjac-i"/><path class="gwfwt7bxc"/><path class="llps18bih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-poedit" /></template>
<style>
.agy9f0mgq {
  d: path("M25.1 11h77.8c4.9 0 6.68.51 8.47 1.47s3.2 2.36 4.16 4.16c.96 1.79 1.47 3.57 1.47 8.47v77.8c0 4.9-.51 6.68-1.47 8.47s-2.37 3.2-4.16 4.16s-3.57 1.47-8.47 1.47H25.1c-4.9 0-6.68-.51-8.47-1.47q-2.71-1.46-4.16-4.16c-1.45-2.7-1.47-3.57-1.47-8.47V25.1c0-4.9.51-6.68 1.47-8.47a10 10 0 0 1 4.16-4.16C18.42 11.5 20.2 11 25.1 11");
}

.as_ysvb9k {
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("M4.9 12h22.2v.23H4.9zm0 7.48h22.2v.24H4.9z");
}

.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.do4dhqbxt {
  d: path("M23.13 18h81.74c1.78 0 2.43.19 3.08.53q1 .53 1.52 1.52c.34.65.53 1.3.53 3.08v81.74c0 1.78-.19 2.43-.53 3.08a3.6 3.6 0 0 1-1.52 1.52c-.65.34-1.3.53-3.08.53H23.13c-1.78 0-2.43-.19-3.08-.53a3.6 3.6 0 0 1-1.52-1.52c-.34-.65-.53-1.3-.53-3.08V23.13c0-1.79.19-2.43.53-3.08q.53-1 1.52-1.52c.65-.34 1.3-.53 3.08-.53");
}

.gfy_s4b2q {
  stop-color: var(--svg-color--ececec, #ececec);
}

.gwfwt7bxc {
  fill: var(--svg-color--1595e0, #1595e0);
  d: path("M9.9 14.5a.5.5 0 0 0-.42.23q-.2.3-.2 1.13c0 .48.07.88.2 1.11q.16.24.43.24q.64.02.63-1.35q0-.84-.2-1.13a.5.5 0 0 0-.43-.23m0 3.04c-.78 0-1.22-.54-1.27-1.53l-.04-.05h-.32l-.04.05v.9c0 .18.01.21.03.23s.04.03.19.03q.06.01.07.07v.17q0 .07-.07.07H7.38a.1.1 0 0 1-.07-.07v-.17q0-.06.07-.07c.22 0 .24-.02.24-.27v-2.1c0-.18-.01-.21-.03-.23s-.05-.03-.21-.03a.1.1 0 0 1-.07-.07v-.17q0-.07.07-.07h1.08q.06 0 .07.07v.17q0 .06-.07.07c-.15 0-.17 0-.19.02s-.03.06-.03.25v.76q0 .05.04.05h.33q.04 0 .04-.04c.08-.9.53-1.41 1.26-1.41c.8 0 1.26.61 1.26 1.69q0 .85-.35 1.3q-.35.38-.92.38");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5h5b149g {
  stroke: var(--svg-color--411400, #411400);
  stroke-opacity: 0.3;
  d: path("M102.9 11.5c4.76 0 6.5.48 8.24 1.41a9.5 9.5 0 0 1 3.95 3.95c.93 1.75 1.41 3.48 1.41 8.24v77.8c0 4.76-.48 6.5-1.4 8.24a9.5 9.5 0 0 1-3.96 3.95c-1.74.93-3.48 1.41-8.24 1.41H25.1c-4.76 0-6.5-.48-8.24-1.41a9.5 9.5 0 0 1-3.95-3.95c-.93-1.75-1.4-3.48-1.4-8.24V25.1c0-4.76.47-6.5 1.4-8.24a9.5 9.5 0 0 1 3.95-3.95c1.75-.93 3.48-1.41 8.24-1.41z");
}

.llps18bih {
  fill: var(--svg-color--c057ea, #c057ea);
  d: path("m9.04 6.97l-.37.12l-.03.04v.59a.04.04 0 0 0 .04.04l.04-.02l.15-.22l.05-.03q.03 0 .05.02l.24.18l.02.01h.02q.03 0 .03-.04V7.1l.02-.04V7a.04.04 0 0 0-.05-.02h-.06zM8.67 8a.04.04 0 0 0-.04.05v.24q0 .04.03.04q.36.12.53.3l.05.01q.03 0 .03-.04v-.56L9.25 8h-.13zm1.2-.56a.04.04 0 0 0-.05.05V9.5q0 .04.05.04h.53q.03 0 .04-.04V7.49a.04.04 0 0 0-.04-.05zM8.15 10.3a.1.1 0 0 1-.07-.06V9.13a.04.04 0 0 0-.05-.05L8 9.1a3 3 0 0 1-.58.59l-.04-.02l-.05-.06v-.08a4 4 0 0 0 .6-1.51L7.89 8h-.47l-.06-.05l-.02-.08a.1.1 0 0 1 .06-.08h.63q.05 0 .05-.05v-.46q0-.03-.02-.04h-.03l-.6.08h-.01q-.06 0-.07-.04l-.02-.06a.1.1 0 0 1 .05-.08a6 6 0 0 0 1.43-.7l.04.02l.48.38l.02.05q0 .03-.02.05l-.02.02L9.3 7q.01.02.05.03h.02l.42.18h.67l.14-.2a.1.1 0 0 1 .1-.01l.45.33q.05.05.02.1a.3.3 0 0 1-.13.09l-.03.04v2.4c0 .08-.2.18-.5.18a.1.1 0 0 1-.06-.07V9.8a.04.04 0 0 0-.04-.04h-.53a.04.04 0 0 0-.05.04v.2c0 .05-.08.23-.49.23l-.06-.06v-.98a.04.04 0 0 0-.07-.04a.3.3 0 0 1-.16.05a.3.3 0 0 1-.2-.09l-.03-.04a1 1 0 0 0-.1-.3a.04.04 0 0 0-.05-.02a.04.04 0 0 0-.03.05v1.33c-.02.1-.2.18-.4.18z");
}

.n3082_b6w {
  stop-color: var(--svg-color--ffb822, #ffb822);
}

.r569shb7i {
  stop-color: var(--svg-color--e26c00, #e26c00);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.y4cbjac-i {
  fill: var(--svg-color--e3450d, #e3450d);
  d: path("M9.56 22.04h-.02l-1.16-.42l-.08-.05l-.02-.1v-.04l.01-.03l.08-.13l.06-.08l.12-.02l.04.01l1.06.63q.04.03.03.08l-.06.12zm-.35.84l-.04.03l-.29.79a.04.04 0 0 0 .04.05h.61l.03-.01v-.04l-.31-.8zm.6 2.15q-.18 0-.25-.05q-.06-.05-.07-.18q.01-.14.08-.17q.07-.04.23-.04h.06a.04.04 0 0 0 .03-.06l-.13-.33l-.04-.02h-.99l-.04.03l-.11.32v.04l.04.02h.06q.18 0 .24.04q.08.06.08.17q-.01.15-.07.18q-.07.05-.25.05h-.59q-.16 0-.22-.05q-.08-.05-.08-.18q.01-.14.08-.17q.05-.04.18-.04q.04 0 .04-.03l.68-1.81v-.04l-.04-.02h-.17q-.15 0-.23-.05t-.08-.17t.08-.18c.03-.02.09-.05.3-.05h.63q.14 0 .2.05t.1.14l.85 2.13q0 .03.04.03a.3.3 0 0 1 .17.04q.07.06.07.17t-.07.18q-.05.05-.2.05z");
}

</style>
