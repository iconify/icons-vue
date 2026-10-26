<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":291};
const content = `<defs><path id="SVGVIRf9bMc" class="p3qubac1n"/></defs><mask id="SVGzX6QWI5A" class="n1mjunbsu"><use href="#SVGVIRf9bMc"/></mask><g mask="url(#SVGzX6QWI5A)"><path class="p9r67wujg"/><path class="p8a07nbwq"/><path class="gfcob8bcb"/><path class="jp-4abbws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:apache-sedona" /></template>
<style>
.gfcob8bcb {
  fill: var(--svg-color--ebbd5d, #ebbd5d);
  fill-rule: evenodd;
  d: path("m99.742 196.03l47.57 32.883l15.191 10.503l27.14-18.223l109.072 67.043l-10.343 14.731l-98.88-59.996l-4.555 3.066l-22.585 15.156l-25.393-17.549l-37.581-25.978l-137.24 88.305l-9.846-15.059z");
}

.jp-4abbws {
  fill: var(--svg-color--d77d48, #d77d48);
  fill-rule: evenodd;
  d: path("m100.054 154.533l47.836 33.583l15.333 10.503l27.539-18.923l110.056 67.042l-10.441 14.74l-99.766-59.997l-4.6 3.059l-22.788 15.165l-25.615-17.559l-37.917-25.978l-138.481 88.314l-9.936-15.067z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.p3qubac1n {
  d: path("M256 0H0v290.416h256z");
}

.p8a07nbwq {
  fill: var(--svg-color--ca463a, #ca463a);
  d: path("m256.656 198.158l-66.191-40.966l-9.759 6.559l-17.363 11.752l-20.217-14.084l17.691-36.72l27.086-56.248z");
}

.p9r67wujg {
  fill: var(--svg-color--ca463a, #ca463a);
  d: path("m180.05 164.211l-17.372 11.762l-20.217-14.084l-42.403-29.55L0 195.517L96.398 0l63.754 125.159z");
}

</style>
