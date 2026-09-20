<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><filter id="SVGspsfOcGl"><feGaussianBlur in="SourceAlpha" result="blur" stdDeviation="4"/><feOffset dx=".1" dy=".1" in="blur" result="offsetBlur"/><feFlood flood-color="#c4c7ce" result="offsetColor"/><feComposite in="offsetColor" in2="offsetBlur" operator="in" result="offsetBlur"/></filter></defs><g filter="url(#SVGspsfOcGl)"><path class="kg1poccjm"/></g><g filter="url(#SVGspsfOcGl)"><path class="ptf03pb6o"/></g><g filter="url(#SVGspsfOcGl)"><path class="z68a85bxa"/></g><g filter="url(#SVGspsfOcGl)"><circle class="c30ck9sax"/></g><path filter="url(#SVGspsfOcGl)" class="nfcqh32bm"/><g filter="url(#SVGspsfOcGl)"><path class="tzulkhqix"/></g><g filter="url(#SVGspsfOcGl)"><path class="lmfyembcv"/></g><path class="sf_funtjw"/><path class="pyrjaybiw"/><path class="iai7ssbay"/><circle class="hcmxv4byo"/><path class="juj71v8rl"/><path class="tz581_bvv"/><path class="zldg0xbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-yeoman" /></template>
<style>
.c30ck9sax {
  cx: 15.981px;
  cy: 13.997px;
  r: 3.13px;
}

.hcmxv4byo {
  cx: 15.981px;
  cy: 13.997px;
  r: 3.13px;
  fill: var(--svg-color--050505, #050505);
}

.iai7ssbay {
  fill: var(--svg-color--050505, #050505);
  d: path("M28.63 19.194H3.351l-.782-2.347h26.862Z");
}

.juj71v8rl {
  fill: var(--svg-color--dd002a, #dd002a);
  d: path("M15.981 16.735A2.738 2.738 0 1 1 18.72 14a2.743 2.743 0 0 1-2.739 2.735m0-5.123A2.384 2.384 0 1 0 18.366 14a2.377 2.377 0 0 0-2.384-2.384Zm0 4.359A1.975 1.975 0 1 1 17.956 14a1.976 1.976 0 0 1-1.975 1.972Zm0-3.707a1.714 1.714 0 1 0 1.719 1.714a1.71 1.71 0 0 0-1.714-1.714Zm.5 1.025l.894-.652l-.689.876l1.08-.279l-.95.577l1.1.13l-1.1.186l1.006.522l-1.08-.224l.727.838l-.931-.6l.373 1.043l-.652-.894l-.019 1.118l-.279-1.08l-.428 1.025l.112-1.1l-.764.8l.5-.987l-1.006.466l.838-.745l-1.118.075L15.143 14l-1.062-.335l1.118.019l-.876-.689l1.025.41l-.559-.95l.8.764l-.186-1.1l.484 1.006l.224-1.08l.093 1.118l.615-.931Z");
}

.kg1poccjm {
  d: path("M25.706 16.847L27.4 7.03S24.849 2 16.037 2C5.344 2 4.562 7.03 4.562 7.03l1.714 9.817Z");
}

.lmfyembcv {
  d: path("M8.977 29.913a9.24 9.24 0 0 1-6.352-1.341s2.328-5.626 6.875-6.763s6.483 1.174 6.483 1.174c.017 2.291-3.132 6.427-7.006 6.93");
}

.nfcqh32bm {
  d: path("M15.981 16.735A2.738 2.738 0 1 1 18.72 14a2.743 2.743 0 0 1-2.739 2.735m0-5.123A2.384 2.384 0 1 0 18.366 14a2.377 2.377 0 0 0-2.384-2.384Zm0 4.359A1.975 1.975 0 1 1 17.956 14a1.976 1.976 0 0 1-1.975 1.972Zm0-3.707a1.714 1.714 0 1 0 1.719 1.714a1.71 1.71 0 0 0-1.714-1.714Zm.5 1.025l.894-.652l-.689.876l1.08-.279l-.95.577l1.1.13l-1.1.186l1.006.522l-1.08-.224l.727.838l-.931-.6l.373 1.043l-.652-.894l-.019 1.118l-.279-1.08l-.428 1.025l.112-1.1l-.764.8l.5-.987l-1.006.466l.838-.745l-1.118.075L15.143 14l-1.062-.335l1.118.019l-.876-.689l1.025.41l-.559-.95l.8.764l-.186-1.1l.484 1.006l.224-1.08l.093 1.118l.615-.931Z");
}

.ptf03pb6o {
  d: path("m5.549 12.637l.727 4.21h19.43l.726-4.21z");
}

.pyrjaybiw {
  fill: var(--svg-color--dd002a, #dd002a);
  d: path("m5.549 12.637l.727 4.21h19.43l.727-4.21z");
}

.sf_funtjw {
  fill: var(--svg-color--050505, #050505);
  d: path("M25.706 16.847L27.4 7.03S24.849 2 16.037 2C5.344 2 4.562 7.03 4.562 7.03l1.714 9.817Z");
}

.tz581_bvv {
  fill: var(--svg-color--4f1907, #4f1907);
  d: path("M15.981 22.983s1.937-2.31 6.483-1.174s6.874 6.762 6.874 6.762a9.24 9.24 0 0 1-6.352 1.341c-3.875-.502-7.023-4.637-7.005-6.929");
}

.tzulkhqix {
  d: path("M15.981 22.983s1.937-2.31 6.483-1.174s6.874 6.762 6.874 6.762a9.24 9.24 0 0 1-6.352 1.341c-3.875-.502-7.023-4.637-7.005-6.929");
}

.z68a85bxa {
  d: path("M28.63 19.194H3.351l-.782-2.347h26.862z");
}

.zldg0xbbp {
  fill: var(--svg-color--4f1907, #4f1907);
  d: path("M8.977 29.913a9.24 9.24 0 0 1-6.352-1.341s2.328-5.626 6.875-6.763s6.483 1.174 6.483 1.174c.017 2.291-3.132 6.427-7.006 6.93");
}

</style>
