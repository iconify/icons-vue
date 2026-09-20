<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="msmzctb6d"/><path class="om27rfbru"/><path class="kd1zn9i8z"/><path class="eqh8asb3q"/><path class="gp-3f7b3d"/><path class="inanyf6ku"/><path class="nqxabdqvc"/><path class="h7dkm4b3f"/><path class="rcc1z8bdn"/><path class="ge7qsvbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:japanese-post-office" /></template>
<style>
.eqh8asb3q {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M6 19h24v16H6z");
}

.ge7qsvbyt {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m8 5l10-5l10 5z");
}

.gp-3f7b3d {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M8 5h20v31H8z");
}

.h7dkm4b3f {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M16 32h4v4h-4z");
}

.inanyf6ku {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M10 20h16v4H10zm0 6h16v4H10z");
}

.kd1zn9i8z {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M2 20h32v4H2zm0 6h32v4H2z");
}

.msmzctb6d {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M0 18v16a2 2 0 0 0 2 2h32a2 2 0 0 0 2-2V18z");
}

.nqxabdqvc {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M14 13h2v18h-2zm6 0h2v18h-2z");
}

.om27rfbru {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m0 18l18-6.352L36 18z");
}

.rcc1z8bdn {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M13 7h10v2H13zm0 4v2h4v4h2v-4h4v-2z");
}

</style>
