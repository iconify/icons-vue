<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGh3xaXcdF" cx="-2.176" cy="-818.913" r="48.27" gradientTransform="matrix(.36 .402 .222 -.163 197.796 -86.468)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o5tfh3bca"/><stop offset=".3" class="us7-fvb-i"/></radialGradient><radialGradient id="SVGqWKFNclI" cx="4199.973" cy="-1187.763" r="83.239" gradientTransform="matrix(.031 .03 .075 -.062 -28.337 -144.76)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o5tfh3bca"/><stop offset="1" class="us7-fvb-i"/></radialGradient><radialGradient id="SVGwpq5AceR" cx="-264.938" cy="-509.943" r="27.886" gradientTransform="matrix(-1.048 -.5 -1.117 .527 -829.648 192.721)" gradientUnits="userSpaceOnUse"><stop offset="0" class="y6fssjfyp"/><stop offset=".15" class="us7-fvb-i"/></radialGradient></defs><path class="rzhsr1syz"/><path class="lcc31bcrw"/><path class="kkwyvbi6x"/><path class="oro4ph-qn"/><path class="ri9sth8ao"/><path class="vgdqacbla"/><path stroke="url(#SVGh3xaXcdF)" class="tozzbtbtr"/><path stroke="url(#SVGqWKFNclI)" class="oq-mh_n8i"/><path stroke="url(#SVGwpq5AceR)" class="y5y8rhbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-paket" /></template>
<style>
.kkwyvbi6x {
  fill: var(--svg-color--0663b4, #0663b4);
  d: path("M16 29.9V15.989L2.087 9.077H2v13.89l13.956 6.956Z");
}

.lcc31bcrw {
  fill: var(--svg-color--0568c1, #0568c1);
  d: path("m2 9.033l14 6.956l14-6.956v13.934l-14.044 6.956L2 22.967Z");
}

.o5tfh3bca {
  stop-color: var(--svg-color--7ce1ff, #7ce1ff);
}

.oq-mh_n8i {
  fill: var(--svg-color--2aa7c9, #2aa7c9);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--76-717px, 76.717px);
  d: path("M8.558 56.835s9.942-6.825 10-7");
}

.oro4ph-qn {
  fill: var(--svg-color--add4f7, #add4f7);
  d: path("m7.709 6.211l13.978 6.956l2.844-1.4l-14.022-6.956Z");
}

.ri9sth8ao {
  fill: var(--svg-color--99c7f2, #99c7f2);
  d: path("m21.687 13.167l2.844-1.4v4.375l-.766-.131l-.809.989l-1.269-.087Z");
}

.rzhsr1syz {
  fill: var(--svg-color--0a6ec9, #0a6ec9);
  d: path("m2 9.033l14-6.956l14 6.956v.919l-14 6.956L2 9.974Z");
}

.tozzbtbtr {
  fill: none;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--76-717px, 76.717px);
  d: path("M18.558 49.816c.061-.183-7-7.561-7-7.561");
}

.us7-fvb-i {
  stop-color: var(--svg-color--7ce1ff, #7ce1ff);
  stop-opacity: 0;
}

.vgdqacbla {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("m13.112 21.545l-4.725-2.362c-.262-.131-.481.022-.481.35V22.7a1 1 0 0 0 .481.831l4.747 2.369c.262.131.481-.022.481-.35v-3.195a1.04 1.04 0 0 0-.503-.81m-1.072 2.6l-3.018-1.506a.53.53 0 0 1-.241-.438c0-.175.109-.262.241-.2l3.019 1.509a.53.53 0 0 1 .241.438c-.001.179-.11.266-.241.2Zm.438-1.094L9.022 21.3a.53.53 0 0 1-.241-.438c0-.175.109-.262.241-.2l3.456 1.75a.53.53 0 0 1 .241.438c0 .205-.11.27-.241.205Z");
}

.y5y8rhbdl {
  fill: none;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--100px, 100px);
  d: path("M8.73 57.121h1.124");
}

.y6fssjfyp {
  stop-color: var(--svg-color--7ce1ff, #7ce1ff);
  stop-opacity: 0.8;
}

</style>
