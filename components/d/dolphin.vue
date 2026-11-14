<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7ol_o72u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dolphin" /></template>
<style>
.u7ol_o72u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.357 18.864l1.471-2.451q2.974-7.24 7.311-9.351l-.622-2.905q-.032-.146-.005-.292q.027-.147.108-.272t.204-.21t.269-.116q.161-.035.321.001q.161.036.292.136l4.086 3.125q3.164.424 6.272 3.977q.099.112.146.254q.048.141.038.29t-.076.282t-.178.232q-.136.12-.312.164l-3 .75q-.131.032-.265.017q-6.272-.697-11.393 5.734l.223 2.453q.013.149-.031.291q-.044.143-.14.257q-.095.115-.227.184q-.133.069-.281.083q-.151.014-.296-.033q-.145-.046-.26-.145L4.473 20H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.208.107-.386");
}

</style>
