<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":276};
const content = `<defs><linearGradient x1="47.271%" y1="-17.693%" x2="61.471%" y2="99.941%" id="ssvg-id-aia"><stop offset="0%" class="g3y8oibkp"/><stop offset="21.64%" class="oqshz6brn"/><stop offset="73.09%" class="guti52q2o"/><stop offset="100%" class="sd46ukbey"/></linearGradient><linearGradient x1="0%" y1="49.999%" x2="100%" y2="49.999%" id="ssvg-id-aib"><stop offset="0%" class="g3y8oibkp"/><stop offset="21.64%" class="oqshz6brn"/><stop offset="73.09%" class="guti52q2o"/><stop offset="100%" class="sd46ukbey"/></linearGradient><linearGradient x1="49.999%" y1="-.02%" x2="49.999%" y2="99.981%" id="ssvg-id-aic"><stop offset="0%" class="sd46ukbey"/><stop offset="42.13%" class="mkjodcbdb"/><stop offset="69.37%" class="nhuu3xhfa"/><stop offset="92.33%" class="l585m5dvr"/><stop offset="100%" class="f9hvkcchg"/></linearGradient></defs><path fill="url(#ssvg-id-aia)" class="xt7q5xbel"/><ellipse class="ocr65ku5f"/><path fill="url(#ssvg-id-aib)" class="rsjd5zbcy"/><path fill="url(#ssvg-id-aic)" class="k2ec0rx-h"/><path class="mmn2wqbod"/><path class="slq18xueu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ai" /></template>
<style>
.f9hvkcchg {
  stop-color: var(--svg-color--ffa000, #FFA000);
}

.g3y8oibkp {
  stop-color: var(--svg-color--ffd54f, #FFD54F);
}

.guti52q2o {
  stop-color: var(--svg-color--ffc516, #FFC516);
}

.k2ec0rx-h {
  d: path("M183.785 243.75c-16.396 7.253-34.542 13.986-55.8 13.29c-31.212-1.016-50.058-10.743-61.174-16.108c-5.243-2.525 26.493-14.983 64.676-14.983c26.506-.008 63.15 13.012 52.298 17.802z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l585m5dvr {
  stop-color: var(--svg-color--ffa701, #FFA701);
}

.mkjodcbdb {
  stop-color: var(--svg-color--ffbe06, #FFBE06);
}

.mmn2wqbod {
  d: path("M109.059 179.138c0-6.368-4.266-11.502-9.543-11.502c-5.28 0-9.555 5.147-9.555 11.502c0 1.107-.008 5.251-.008 6.359c0 6.35 4.278 11.493 9.555 11.493s9.55-5.155 9.55-11.493v-6.36z");
  fill: var(--svg-color--ff8f00, #FF8F00);
}

.nhuu3xhfa {
  stop-color: var(--svg-color--ffb605, #FFB605);
}

.ocr65ku5f {
  fill: var(--svg-color--ffe082, #FFE082);
  cx: 128px;
  cy: 128.782px;
  rx: 128px;
  ry: 24.484px;
}

.oqshz6brn {
  stop-color: var(--svg-color--ffd03d, #FFD03D);
}

.rsjd5zbcy {
  d: path("M255.996 129.776c0-67.113-51.967-123.421-117.974-128.543C134.712.986 131.372 0 128 0c-3.343 0-6.657 1.023-9.934 1.271C52.013 6.342 0 62.663 0 129.776h.1c-.037 4.194-.1.386-.1.65c0 13.532 57.311 24.417 128 24.417c70.697 0 128-10.856 128-24.38c0-.26-.059 3.507-.1-.687h.096z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sd46ukbey {
  stop-color: var(--svg-color--ffc107, #FFC107);
}

.slq18xueu {
  d: path("M159.394 179.138c0-6.368-4.518-11.502-9.803-11.502c-5.277 0-9.681 5.147-9.681 11.502c0 1.107-.076 5.251-.076 6.359c0 6.35 4.501 11.493 9.778 11.493s9.782-5.147 9.782-11.493v-6.36z");
  fill: var(--svg-color--ff8f00, #FF8F00);
}

.xt7q5xbel {
  d: path("M128 257.04c3.348 0 6.666-.122 9.942-.387c1.967-.147 7.211-.746 9.158-.973c3.288-.42 7.47 19.958 10.688 19.304c3.423-.697 2.588-21.64 5.907-22.61C217.016 236.923 256 192.695 256 129.777H0C0 188.5 36.735 234.028 87.666 250.924c2.94.973 2.79 23.447 5.826 24.206c3.13.789 9.452-20.415 12.673-19.857c3.876.671 7.82 1.124 11.81 1.435c3.309.247 6.652.331 10.025.331z");
}

</style>
