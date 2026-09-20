<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e2tpn0o9h"/><path class="zvm2qbe9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-environments-opened" /></template>
<style>
.e2tpn0o9h {
  fill: var(--svg-color--055d7f, #055d7f);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21zm-7.2 2.1h7.1v2.1h-8.1zm5.5 6.1H6.6v-1.9h20.8v7.626z");
}

.ft5dv1b6b {
  fill: none;
}

.zvm2qbe9r {
  fill: var(--svg-color--99b8c4, #99b8c4);
  d: path("m25.999 26.903l.62-.615c2.865.093 2.909-.007 3.035-.302l.787-1.916l.058-.182l-.064-.159c-.033-.084-.137-.334-1.926-2.04v-.898c2.064-1.988 2.02-2.09 1.902-2.381l-.783-1.937c-.118-.29-.163-.404-3.008-.326l-.619-.64c.064-.943.031-1.89-.097-2.825l-.08-.181l-2.046-.895c-.302-.138-.408-.187-2.34 1.917l-.869-.013c-1.99-2.123-2.083-2.085-2.381-1.965l-1.903.77c-.298.12-.403.163-.288 3.053l-.614.613c-2.864-.094-2.908.008-3.033.301l-.789 1.917l-.062.184l.065.16c.034.082.134.33 1.927 2.038v.895c-2.064 1.988-2.02 2.09-1.901 2.382l.783 1.938c.12.297.162.402 3.006.328l.62.643c-.065.942-.033 1.887.094 2.822l.08.182l2.06.9c.299.126.403.17 2.33-1.927l.868.012c1.992 2.126 2.094 2.085 2.385 1.967l1.899-.767c.3-.12.404-.161.284-3.053m-8.16-4.49a3.412 3.412 0 1 1 4.464 1.944a3.45 3.45 0 0 1-4.464-1.944");
}

</style>
