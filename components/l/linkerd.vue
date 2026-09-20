<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":239};
const content = `<defs><linearGradient id="SVGNQcJtdfY" x1="50%" x2="50%" y1="0%" y2="100%"><stop offset="0%" class="lp9wsj0gd"/><stop offset="100%" class="u7n3gubtj"/></linearGradient></defs><path class="yuw4r3kqv"/><path class="p76xcz-lm"/><path class="pd13qjl8s"/><path class="dbjcuvbly"/><g fill="url(#SVGNQcJtdfY)" transform="translate(0 92.444)"><path class="vy907hb3i"/><path class="hy0d27u6u"/><path class="s2brnpz-h"/><path class="dmgq777yn"/><path class="tod4dbbgf"/><path class="zjz0rfbcj"/></g><path class="dsvucpbxk"/><path class="gbyg1dbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:linkerd" /></template>
<style>
.dbjcuvbly {
  fill: var(--svg-color--7ce1c0, #7ce1c0);
  d: path("m194.712 70.374l17.776 10.263l43.508-25.118l-17.782-10.261zm-57.722 53.855l-17.778-10.263l-40.988 23.666l17.777 10.263zm79.903-91.286l-17.782-10.264l-43.502 25.119l17.778 10.265zm-119.005 68.71L80.11 91.39l-40.989 23.665l17.778 10.263zm18.619-76.431l17.778 10.263l43.506-25.118L160.009.104zM.019 92.478l17.778 10.263l40.988-23.664l-17.777-10.265z");
}

.dmgq777yn {
  d: path("m78.232 135.514l17.778 10.263V55.453L78.232 45.187z");
}

.dsvucpbxk {
  fill: var(--svg-color--45c1a8, #45c1a8);
  d: path("m103.108 123.264l17.778 10.263l16.105-9.298l-17.778-10.263zM24.904 78.111l17.778 10.263l16.103-9.298l-17.776-10.263zm39.102 22.576l17.778 10.263l16.103-9.297L80.111 91.39z");
}

.gbyg1dbof {
  fill: var(--svg-color--a2eacf, #a2eacf);
  d: path("m96.002.094l-17.78 10.263l159.993 92.375l17.779-10.263zM56.889 22.676L39.112 32.939l159.991 92.375l17.781-10.263zM0 55.52l159.991 92.375l17.781-10.263L17.778 45.257z");
}

.hy0d27u6u {
  d: path("M216.884 112.933V22.607L199.106 32.87v90.328z");
}

.lp9wsj0gd {
  stop-color: var(--svg-color--4ad8ac, #4ad8ac);
}

.p76xcz-lm {
  fill: var(--svg-color--338090, #338090);
  d: path("m103.118 213.59l17.777 10.265l17.444-10.073l-17.778-10.263z");
}

.pd13qjl8s {
  fill: var(--svg-color--45c1a8, #45c1a8);
  d: path("M168.884 198.188V177.66l-76.546-44.195l-5.226 3.016l.008.006v14.494zm-81.764-2.045L160 238.222l17.781-10.263l-90.661-52.345z");
}

.s2brnpz-h {
  d: path("M159.994 55.451v90.327l17.779-10.264V45.186z");
}

.tod4dbbgf {
  d: path("M56.899 32.871v90.326l-17.778-10.263V22.607z");
}

.u7n3gubtj {
  stop-color: var(--svg-color--4076c4, #4076c4);
}

.vy907hb3i {
  d: path("M238.218 10.29v90.327l17.777-10.265V.027z");
}

.yuw4r3kqv {
  fill: var(--svg-color--40a0b4, #40a0b4);
  d: path("m238.218 141.655l17.777 10.263v-96.4l-17.777-10.266zM0 55.519v96.406l17.778-10.269V45.254zm78.232 172.439l17.778 10.263l42.329-24.439l-17.778-10.263z");
}

.zjz0rfbcj {
  d: path("m.01 90.352l17.777 10.263V10.29L.01.025z");
}

</style>
