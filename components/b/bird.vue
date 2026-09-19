<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hwc9k9bnb"/><path class="nz5arp5st"/><path class="cqqfb30dv"/><ellipse class="mfev2wb4e"/><path class="aq-zim-0n"/><ellipse class="kmwierb5c"/><ellipse class="b_txirm5g"/><path class="f85xnyn2b"/><path class="e7e_w-bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:bird" /></template>
<style>
.aq-zim-0n {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M25.527 21.625c0 2.192-1.466 3.968-3.27 3.968c-1.808 0-3.274-1.775-3.274-3.968c0-2.189 1.466-3.968 3.274-3.968c1.804 0 3.27 1.779 3.27 3.968");
}

.b_txirm5g {
  cx: 42.02px;
  cy: 21.625px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 3.271px;
  ry: 3.968px;
}

.cqqfb30dv {
  fill: var(--svg-color--7094a6, #7094a6);
  d: path("M8.03 38.13c0 9.657 10.778 17.479 24.09 17.479c13.309 0 24.09-7.821 24.09-17.479c0-9.648-10.781-33.452-24.09-33.452c-13.312 0-24.09 23.804-24.09 33.452");
}

.e7e_w-bew {
  fill: var(--svg-color--f79420, #f79420);
  d: path("M26.03 25.718c0-2.895 2.726-.709 6.084-.709s6.084-2.185 6.084.709c0 2.899-2.726 8.377-6.084 8.377s-6.084-5.478-6.084-8.377");
}

.f85xnyn2b {
  fill: var(--svg-color--f05a2a, #f05a2a);
  d: path("M26.03 27.692c0-2.895 2.725-.708 6.085-.708c3.362 0 6.084-2.187 6.084.708c0 2.9-2.723 8.378-6.084 8.378s-6.085-5.478-6.085-8.378");
}

.hwc9k9bnb {
  fill: var(--svg-color--f79420, #f79420);
  d: path("M25.772 60.8c0 1.768-.836 3.2-1.866 3.2s-1.866-1.433-1.866-3.2v-7.393c0-1.768.835-3.2 1.866-3.2c1.03 0 1.866 1.433 1.866 3.2zm13.814 0c0 1.768-.836 3.2-1.866 3.2s-1.866-1.433-1.866-3.2v-7.393c0-1.768.836-3.2 1.866-3.2s1.866 1.433 1.866 3.2z");
}

.kmwierb5c {
  cx: 42.02px;
  cy: 21.395px;
  fill: var(--svg-color--f4f5f5, #f4f5f5);
  rx: 4.932px;
  ry: 5.98px;
}

.mfev2wb4e {
  cx: 22.255px;
  cy: 21.395px;
  fill: var(--svg-color--f4f5f5, #f4f5f5);
  rx: 4.932px;
  ry: 5.98px;
}

.nz5arp5st {
  fill: var(--svg-color--58767d, #58767d);
  d: path("M.267 40.94c0-4.198 6.1-2.936 10.968-2.936c4.872 0 9.199-.078 9.199 4.118c0 4.204-3.95 7.607-8.818 7.607c-4.872 0-11.349-4.586-11.349-8.789m63.467 0c0-4.198-6.1-2.936-10.973-2.936c-4.871 0-9.198-.078-9.198 4.118c0 4.204 3.95 7.607 8.821 7.607c4.869 0 11.35-4.586 11.35-8.789");
}

</style>
