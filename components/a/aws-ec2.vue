<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGeyciVcvH" x1="0%" x2="100%" y1="100%" y2="0%"><stop offset="0%" class="pkxkyybrw"/><stop offset="100%" class="sl1qm9b9s"/></linearGradient></defs><path fill="url(#SVGeyciVcvH)" class="tmbkaq7lv"/><path class="m7e2klknr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:aws-ec2" /></template>
<style>
.m7e2klknr {
  fill: var(--svg-color--fff, #fff);
  d: path("M86.4 169.6h80v-80h-80zm86.4-80h12.8V96h-12.8v12.8h12.8v6.4h-12.8v9.6h12.8v6.4h-12.8V144h12.8v6.4h-12.8v12.8h12.8v6.4h-12.8v.435a5.97 5.97 0 0 1-5.965 5.965h-.435v12.8H160V176h-12.8v12.8h-6.4V176h-9.6v12.8h-6.4V176H112v12.8h-6.4V176H92.8v12.8h-6.4V176h-.435A5.97 5.97 0 0 1 80 170.035v-.435h-9.6v-6.4H80v-12.8h-9.6V144H80v-12.8h-9.6v-6.4H80v-9.6h-9.6v-6.4H80V96h-9.6v-6.4H80v-.435a5.97 5.97 0 0 1 5.965-5.965h.435V70.4h6.4v12.8h12.8V70.4h6.4v12.8h12.8V70.4h6.4v12.8h9.6V70.4h6.4v12.8H160V70.4h6.4v12.8h.435a5.97 5.97 0 0 1 5.965 5.965zm-41.6 121.203a.4.4 0 0 1-.397.397H45.197a.4.4 0 0 1-.397-.397v-85.606a.4.4 0 0 1 .397-.397H64v-6.4H45.197a6.805 6.805 0 0 0-6.797 6.797v85.606a6.805 6.805 0 0 0 6.797 6.797h85.606a6.805 6.805 0 0 0 6.797-6.797V195.2h-6.4zm86.4-165.606v85.606a6.805 6.805 0 0 1-6.797 6.797H192v-6.4h18.803a.4.4 0 0 0 .397-.397V45.197a.4.4 0 0 0-.397-.397h-85.606a.4.4 0 0 0-.397.397V64h-6.4V45.197a6.805 6.805 0 0 1 6.797-6.797h85.606a6.805 6.805 0 0 1 6.797 6.797");
}

.pkxkyybrw {
  stop-color: var(--svg-color--c8511b, #c8511b);
}

.sl1qm9b9s {
  stop-color: var(--svg-color--f90, #f90);
}

.tmbkaq7lv {
  d: path("M0 0h256v256H0z");
}

</style>
