<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozsm5jb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:femur-alt-rounded" /></template>
<style>
.ozsm5jb_h {
  fill: currentColor;
  d: path("M13.308 12.577q.328 0 .549-.23q.22-.23.22-.54q0-.13-.073-.382q.255-.062.414-.264t.159-.469q0-.329-.22-.549t-.55-.22q-.267 0-.469.156t-.263.417l-3.67-1.769q.084-.075.249-.535q0-.328-.22-.549q-.22-.22-.55-.22q-.309 0-.539.22t-.23.55q0 .188.099.357q-.256.062-.427.264t-.171.494q0 .31.23.539q.229.23.539.23q.254 0 .456-.14q.201-.139.282-.362l3.63 1.73q-.037.04-.214.503q0 .31.23.539q.229.23.539.23m3.89-3.888q.379.609.59 1.29T18 11.425v9.364q0 .509-.351.86t-.86.351l-5.135-.02q-.348 0-.603-.189t-.38-.512q-.85-2.485-.674-4.751t.2-2.86q-.007-.116-.03-.212t-.163-.115q-.29-.047-2.053-.449q-1.763-.401-3.688-1.705q-.367-.237-.413-.672t.216-.784l3.817-5.11q.267-.348.683-.45t.801.085l5.704 2.598q.685.292 1.217.758t.91 1.076");
}

</style>
