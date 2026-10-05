<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":1.28,"height":1.28};
const content = `<defs><clipPath id="SVGHsGyoden"><path class="fl_nzx77m powerclip"/></clipPath></defs><path clip-path="url(#SVGHsGyoden)" class="ycyscbcdv"/><path class="ypav9sblr"/><path class="uw-u51rbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-tasks-json" /></template>
<style>
.fl_nzx77m {
  fill: none;
  stroke-width: var(--svg-stroke-width--0-04px, 0.04px);
  d: path("M-4.8-4.92H6.1v11.1H-4.8zM.99.57v.08h.104V.57z");
}

.uw-u51rbm {
  fill: var(--svg-color--f5df19, #f5df19);
  stroke: var(--svg-color--fbc12d, #fbc12d);
  stroke-width: var(--svg-stroke-width--0-008px, 0.008px);
  d: path("M.64.915A.06.06 0 0 0 .68.902A.06.06 0 0 0 .7.868A.4.4 0 0 0 .704.794q0-.052.002-.069a.1.1 0 0 1 .01-.042a.1.1 0 0 1 .019-.025a.1.1 0 0 1 .029-.015L.803.64h.018v.05H.81A.06.06 0 0 0 .768.7a.1.1 0 0 0-.01.052a1 1 0 0 1-.004.103a.1.1 0 0 1-.02.052a.1.1 0 0 1-.042.032a.1.1 0 0 1 .05.044a.2.2 0 0 1 .016.097v.072a.04.04 0 0 0 .013.03a.1.1 0 0 0 .04.008h.01v.05H.803a.1.1 0 0 1-.044-.006a.1.1 0 0 1-.033-.023a.1.1 0 0 1-.017-.04l-.004-.082a.4.4 0 0 0-.006-.077a.06.06 0 0 0-.02-.034A.06.06 0 0 0 .64.966zm.6.051a.06.06 0 0 0-.04.013a.06.06 0 0 0-.02.034a.4.4 0 0 0-.005.078l-.004.08a.1.1 0 0 1-.017.042a.1.1 0 0 1-.033.023a.1.1 0 0 1-.044.005h-.018v-.049h.01a.1.1 0 0 0 .04-.008a.04.04 0 0 0 .012-.03q.002-.012.002-.073a.2.2 0 0 1 .015-.096a.1.1 0 0 1 .05-.044a.1.1 0 0 1-.043-.033a.1.1 0 0 1-.019-.051a1 1 0 0 1-.003-.103a.1.1 0 0 0-.01-.053a.06.06 0 0 0-.044-.011h-.01V.64h.018l.038.004a.1.1 0 0 1 .03.014a.1.1 0 0 1 .018.026a.1.1 0 0 1 .01.042q.002.017.002.069a.4.4 0 0 0 .006.074a.06.06 0 0 0 .02.034a.06.06 0 0 0 .04.013z");
}

.ycyscbcdv {
  fill: var(--svg-color--gray, gray);
  d: path("M.48 1.12h-.2V.28H.4V.4h.48V.28H1v.36h.08V.28A.08.08 0 0 0 1 .2H.88V.16A.08.08 0 0 0 .8.08H.48A.08.08 0 0 0 .4.16V.2H.28A.08.08 0 0 0 .2.28v.84a.08.08 0 0 0 .08.08h.2zm0-.96H.8v.16H.48z");
}

.ypav9sblr {
  fill: var(--svg-color--gray, gray);
  d: path("M.334.729h.395v.05H.334zm0 .204h.35v.05h-.35zm0-.407h.607v.05H.334z");
}

</style>
