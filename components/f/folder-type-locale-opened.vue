<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p--tkib0o"/><path class="mukxo8vuo"/><path class="x634fgboz"/><path class="r3eb6ibmq"/><path class="uaip69b_l"/><path class="m_61gzb5y"/><path class="t49txybyf"/><path class="e_j2f_b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-locale-opened" /></template>
<style>
.e_j2f_b6f {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M13.792 18.856c.458-1.18.908-2.362 1.365-3.542h1.327q.107.273.212.548c.335.865.665 1.732 1 2.6s.659 1.714.989 2.572l.267.692h-1.165q-.249-.758-.494-1.518h-2.944q-.245.76-.493 1.518h-1.165l1.1-2.866m.886.5h2.288c-.382-1-.76-2.008-1.144-3.011c-.384 1.003-.761 2.009-1.143 3.012Z");
}

.m_61gzb5y {
  fill: var(--svg-color--4f8bf5, #4f8bf5);
  d: path("M11.4 10a1.4 1.4 0 0 0-1.4 1.4v14.24a1.4 1.4 0 0 0 1.4 1.4h13.632L19.561 10Z");
}

.mukxo8vuo {
  fill: var(--svg-color--7b87db, #7b87db);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.p--tkib0o {
  fill: var(--svg-color--7b87db, #7b87db);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.r3eb6ibmq {
  fill: var(--svg-color--4352b8, #4352b8);
  d: path("M25.03 27.035L21.464 31l-1.297-3.965z");
}

.t49txybyf {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.242 14.216H29.6a1.39 1.39 0 0 1 1.4 1.375v8.419Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uaip69b_l {
  fill: var(--svg-color--617d8b, #617d8b);
  d: path("M29.673 20.03v-.82h-3.955v-1.326h-1.283v1.325H21.91v.82h5.023a7.3 7.3 0 0 1-1.441 2.535c-1.027-1.214-1.031-1.609-1.031-1.609H23.4s.044.591 1.483 2.278a10 10 0 0 1-.822.761l.328 1.024s.494-.425 1.115-1.083a46 46 0 0 0 2.459 2.449l.673-.673c-1.111-1.008-1.925-1.807-2.522-2.449a7.45 7.45 0 0 0 1.786-3.234h1.775Z");
}

.x634fgboz {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("M29.6 31a1.39 1.39 0 0 0 1.4-1.376V15.591a1.39 1.39 0 0 0-1.4-1.376H15.968L21.439 31Z");
}

</style>
