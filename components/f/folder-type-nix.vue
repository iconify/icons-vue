<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGZAMsIc6Y" x1="536.24" x2="540.83" y1="1537.03" y2="1544.97" gradientTransform="matrix(.8 0 0 .8 -414.75 -1206.48)" gradientUnits="userSpaceOnUse"><stop offset="0" class="gdp70qhgy"/><stop offset=".24" class="r98qovb1k"/><stop offset="1" class="va1f5785t"/></linearGradient><linearGradient id="SVGeFm8kdsT" x1="979.2" x2="983.79" y1="718.68" y2="726.62" gradientTransform="rotate(59.9 883.564 -368.28)scale(.8)" href="#SVGZAMsIc6Y"/><linearGradient id="SVGAbVVedCq" x1="-392.84" x2="-388.26" y1="1566.6" y2="1574.53" gradientTransform="rotate(-59.9 -1207.903 352.323)scale(.8)" href="#SVGZAMsIc6Y"/><linearGradient id="SVGzsjEceQk" x1="-441.2" x2="-436.61" y1="-45.76" y2="-37.82" gradientTransform="matrix(-.8 0 0 -.8 -325.52 -15.63)" href="#SVGZAMsIc6Y"/><linearGradient id="SVGU4IBWboV" x1="-257.74" x2="-253.23" y1="1973.17" y2="1981.14" gradientTransform="matrix(.8 0 0 .8 220.49 -1555.43)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vrkn7fbay"/><stop offset=".23" class="jvsny3cfu"/><stop offset="1" class="i8rnxfbsx"/></linearGradient><linearGradient id="SVGdAcoNbyI" x1="-306.31" x2="-301.81" y1="360.59" y2="368.55" gradientTransform="rotate(120.1 -31.602 229.209)scale(.8)" href="#SVGU4IBWboV"/><linearGradient id="SVGTmFpyeni" x1="-1681.52" x2="-1677.01" y1="1210.07" y2="1218.04" gradientTransform="rotate(239.9 -928.27 102.1)scale(.8)" href="#SVGU4IBWboV"/></defs><path class="kipd1lu2j"/><path fill="url(#SVGZAMsIc6Y)" class="d5ksn6wkk"/><path fill="url(#SVGeFm8kdsT)" class="vnu0i6qoe"/><path fill="url(#SVGAbVVedCq)" class="su0dn3b7e"/><path fill="url(#SVGzsjEceQk)" class="splwfybho"/><path fill="url(#SVGU4IBWboV)" class="d5ksn6wkk"/><path fill="url(#SVGdAcoNbyI)" class="tsvwl491z"/><path fill="url(#SVGTmFpyeni)" class="kpw2wgbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-nix" /></template>
<style>
.d5ksn6wkk {
  fill-rule: evenodd;
  d: path("m16.83 22.29l5 8.69h-2.3l-1.33-2.32L16.86 31h-1.15l-.58-1l1.92-3.3l-1.37-2.38Z");
}

.gdp70qhgy {
  stop-color: var(--svg-color--699ad7, #699ad7);
}

.i8rnxfbsx {
  stop-color: var(--svg-color--5277c3, #5277c3);
}

.jvsny3cfu {
  stop-color: var(--svg-color--4a6baf, #4a6baf);
}

.kipd1lu2j {
  fill: var(--svg-color--4a5e7f, #4a5e7f);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.kpw2wgbjx {
  fill-rule: evenodd;
  d: path("m23 25.42l5-8.69l1.17 2l-1.35 2.33h2.68l.57 1l-.58 1h-3.77l-1.38 2.37Z");
}

.r98qovb1k {
  stop-color: var(--svg-color--7eb1dd, #7eb1dd);
}

.splwfybho {
  fill-rule: evenodd;
  d: path("m24.85 21.85l-5-8.7h2.3l1.33 2.34l1.35-2.32H26l.59 1l-1.92 3.3L26 19.84Z");
}

.su0dn3b7e {
  fill-rule: evenodd;
  d: path("M19 25.65h10l-1.13 2h-2.65L26.56 30L26 31h-1.19l-1.89-3.32h-2.74Z");
}

.tsvwl491z {
  fill-rule: evenodd;
  d: path("M22.64 18.46h-10l1.13-2h2.68l-1.33-2.33l.57-1h1.17l1.9 3.32h2.73Z");
}

.va1f5785t {
  stop-color: var(--svg-color--7ebae4, #7ebae4);
}

.vnu0i6qoe {
  fill-rule: evenodd;
  d: path("m18.64 18.71l-5 8.69l-1.17-2l1.35-2.33h-2.69l-.57-1l.58-1H15l1.37-2.37Z");
}

.vrkn7fbay {
  stop-color: var(--svg-color--415e9a, #415e9a);
}

</style>
