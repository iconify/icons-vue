<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJQkOYcCS)" class="r4i437pya"/><path clip-rule="evenodd" class="pbgyd7uxx"/></g><defs><linearGradient id="SVGJQkOYcCS" x1="12" x2="11.9" y1="8" y2="15.62" gradientUnits="userSpaceOnUse"><stop class="qftbm5bzc"/><stop offset=".2" class="zatfd3bno"/><stop offset=".46" class="k6g5a9chp"/><stop offset=".71" class="go-z88b4f"/><stop offset=".86" class="cf9nlycvp"/><stop offset="1" class="ppv0zrbli"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:carat-background" /></template>
<style>
.cf9nlycvp {
  stop-color: var(--svg-color--aea16d, #aea16d);
}

.ft5dv1b6b {
  fill: none;
}

.go-z88b4f {
  stop-color: var(--svg-color--fef2c0, #fef2c0);
}

.k6g5a9chp {
  stop-color: var(--svg-color--98763b, #98763b);
}

.pbgyd7uxx {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10 8c-3.596.752-5.46 4.312-6 6c.288-.6 2.16-2 3.056-2.624L6.8 12l1.156-.252l-.72.376c.432-.148 2.216-.06 3.056 0c-1.44 0-2.64.488-3.056.676c1.4-.224 2.616-.32 3.612-.364L9.6 15.4h.612l.328-1h.648l.16 1H12l-1.124-2.968c.78-.032 1.424-.032 1.924-.032l.548-.276l1.252.276l.084.004c.152.012.408.032.64-.092c.288-.148.84-.04 1.076.088h-1.2s.2.1.2.256c0 .16-.532.72-.8.984v-.392c0-.316.132-.524.2-.592H14v2.356c0 .312-.132.392-.2.392h1l-.2-.392v-.784c.132.128.44.468.6.784c.16.312.068.392 0 .392l1.2.196h.748l.184-.86l.748.18l.32.88l.8.2l-1.492-3.6l-1.308 3.2l-1.2-1.568l1.2-1.632l.544-.84c-.12-.06-.252-.184.18-.184S19.22 13.12 20 14c-.576-3.3-4.544-5.376-6.4-6l.4 1.2s2.224.864 2.224 1.052c0 .092-.044.184-.088.28a.64.64 0 0 0-.092.28c0 .064.068.108.16.168c.12.08.276.184.38.396l-1.08-.752h-.36c-.12 0-.336-.272-.516-.5a4 4 0 0 0-.2-.248c-.144-.152-.66.188-.9.372C13.168 9.688 12.38 9 12.2 9c-.144 0-.768.624-1.008.876h-.54c-.092 0-.18.092-.268.188c-.092.092-.18.184-.272.184c-.088 0-.18-.092-.268-.184c-.092-.096-.18-.188-.272-.188c-.144 0-.42.248-.54.372h-.36l-.72.564l-.176-.376C7.632 9.988 8.88 9.452 9.6 9.2zm2 1.5l-.808.936l.36.376l.896-.748H12zm-2.608.752v.56l-.18-.188zm-.54.372l-1.252.752L8.856 11v-.376zm-.536 1.128l2.336-1.316l-.36.564h.9l-1.08.56l-.36-.184l-1.44.372zm4.492-1.5l1.26 1.12l-.9-.372l-.36-.752zm1.44 0l-.54.184l.54.188l.18.188zm.54.56l.72.56l-.72-.184zm-2.52.188l-1.616.752l1.616-.564l.72.56h.18l-.18-.372h-.18zM5.84 15.82L5.2 16l1.28-3.6l1.12 3.2h-.64l-.16-.86l-.64.18zm1.76-.22l1.8-.188l.2-.744c-.16.148-.868.308-1.2.372v-1.68c0-.3.132-.496.2-.56h-1c.2.2.2.28.2.44v1.8c0 .3-.132.496-.2.56m-1.28-1.4l.16-.54l.16.54zm11.388-.54l.184.54h-.372zm-4.108-.412c-.068-.132-.264-.448-.6-.448c-.2 0-.4.052-.4.252c0 .068.16.22.364.412c.352.332.836.784.836 1.156c0 .588-.552.784-1 .784c-.252 0-.452-.08-.6-.136a.7.7 0 0 0-.2-.06v-.588l.144.108c.16.132.352.28.656.28c.336 0 .4-.192.4-.388c0-.128-.212-.32-.456-.548c-.34-.308-.744-.68-.744-1.02c0-.788 1.2-.788 1.6-.396zm-2.768.392l-.18.456h.36z");
}

.ppv0zrbli {
  stop-color: var(--svg-color--f2e4b8, #f2e4b8);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qftbm5bzc {
  stop-color: var(--svg-color--665420, #665420);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zatfd3bno {
  stop-color: var(--svg-color--fbf0b8, #fbf0b8);
}

</style>
