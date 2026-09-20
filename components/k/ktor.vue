<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":243};
const content = `<defs><linearGradient id="SVGLKkSDb8c" x1="23.965%" x2="74.641%" y1="23.965%" y2="74.641%"><stop offset="29.6%" class="u8tcm6c4u"/><stop offset="69.4%" class="b9q93fweg"/><stop offset="100%" class="fm8fght5r"/></linearGradient><linearGradient id="SVG3A0aHc1h" x1="26.206%" x2="74.117%" y1="26.206%" y2="74.117%"><stop offset="10.8%" class="wocloqb2t"/><stop offset="17.3%" class="wd4kgkb9d"/><stop offset="49.2%" class="yed9zep2k"/><stop offset="71.6%" class="n9-hdgo3l"/><stop offset="82.3%" class="ygvu4sbcy"/></linearGradient></defs><path fill="url(#SVGLKkSDb8c)" class="nlll667uu"/><path fill="url(#SVG3A0aHc1h)" class="qu2rs5bzs"/><path class="b_bmqdell"/><path class="pdvir0b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ktor" /></template>
<style>
.b_bmqdell {
  d: path("M161.667 80.833H80.833v80.834h80.834z");
}

.b9q93fweg {
  stop-color: var(--svg-color--5282ff, #5282ff);
}

.fm8fght5r {
  stop-color: var(--svg-color--945dff, #945dff);
}

.n9-hdgo3l {
  stop-color: var(--svg-color--f88316, #f88316);
}

.nlll667uu {
  d: path("m161.667 80.833l-40.249-40.249L80.833 0l-42.68 42.68L0 80.833l80.833 80.834z");
}

.pdvir0b-j {
  fill: var(--svg-color--27282c, #27282c);
  d: path("M312.036 160.523V138.23l7.392-8.69l21.661 30.983h18.715l-29.103-40.998l27.188-31.947h-17.37l-27.553 32.756h-.93V87.578h-15.612v72.945zm59.243-68.949v13.794h-8.893v11.176h8.893v28.967c0 10.813 5.482 15.214 19.336 15.214c2.53.004 5.057-.216 7.549-.657V149.2a36 36 0 0 1-4.446.252c-5.119 0-7.393-2.324-7.393-7.326v-25.582h11.839v-11.171h-11.839V91.574zm64.315 70.11c17.522 0 28.072-10.812 28.072-29.017c0-18.043-10.701-29.012-28.072-29.012s-28.073 11.015-28.073 29.012c0 18.15 10.545 29.018 28.073 29.018m0-11.625c-8.064 0-12.617-6.367-12.617-17.392c0-10.913 4.598-17.335 12.617-17.335c7.958 0 12.611 6.417 12.611 17.335c0 11.02-4.598 17.392-12.611 17.392m40.37 10.459h15.047v-31.135c0-7.831 5.634-12.637 13.855-12.637c2.43 0 5.947.405 7.134.809v-12.94c-1.288-.404-3.825-.657-5.891-.657c-7.236 0-13.132 4.194-14.633 9.752h-.93v-8.842H475.97v55.655z");
}

.qu2rs5bzs {
  d: path("m80.833 161.667l40.249 40.249l40.585 40.584l42.68-42.68l38.153-38.153l-80.833-80.834z");
}

.u8tcm6c4u {
  stop-color: var(--svg-color--00afff, #00afff);
}

.wd4kgkb9d {
  stop-color: var(--svg-color--cd5ca9, #cd5ca9);
}

.wocloqb2t {
  stop-color: var(--svg-color--c757bc, #c757bc);
}

.yed9zep2k {
  stop-color: var(--svg-color--e8744f, #e8744f);
}

.ygvu4sbcy {
  stop-color: var(--svg-color--ff8900, #ff8900);
}

</style>
