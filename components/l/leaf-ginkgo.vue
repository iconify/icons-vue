<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjxiqnbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-ginkgo" /></template>
<style>
.mjxiqnbnq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.241 16.011q-7.275-2.9-8.962-8.805q-.023-.081-.028-.166q-.004-.084.01-.168q.014-.083.047-.161t.082-.147q1.887-2.642 4.511-3.726q2.444-1.009 4.362-.29q.081.03.152.078q.072.047.131.11t.102.137q.044.074.069.156L12 3.95l.283-.921q.025-.082.069-.156q.043-.074.102-.137t.131-.11t.152-.078q1.918-.719 4.362.29q2.624 1.084 4.511 3.726q.049.069.082.147t.047.161q.014.084.01.168q-.005.085-.028.166q-1.689 5.912-8.979 8.811q-.127 3.929-2.212 6.013q-.105.106-.243.163T10 22.25t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q1.654-1.655 1.771-4.959");
}

</style>
