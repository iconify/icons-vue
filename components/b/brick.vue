<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k24_1znie"/><path class="we_us-b9i"/><path class="vmey65b6d"/><ellipse class="j2_4qqslf"/><path class="rinl4yb3v"/><ellipse class="nqu9-v01p"/><path class="v9wqvwzzb"/><ellipse class="jxkqzrb0u"/><path class="zh3rdqbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:brick" /></template>
<style>
.j2_4qqslf {
  cx: 11.189px;
  cy: 17.191px;
  fill: var(--svg-color--c1694f, #c1694f);
  rx: 3.679px;
  ry: 1.84px;
}

.jxkqzrb0u {
  cx: 24.811px;
  cy: 10.087px;
  fill: var(--svg-color--c1694f, #c1694f);
  rx: 3.679px;
  ry: 1.84px;
}

.k24_1znie {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M35.627 10.826L.373 16.56v9.722h.004c-.012.149.129.295.443.473c.727.412 9.835 5.286 10.553 5.639c.895.439 1.441.493 2.206.112c.626-.312 19.236-10.173 20.932-11.074c.863-.459 1.146-.711 1.099-.919h.018z");
}

.nqu9-v01p {
  cx: 18px;
  cy: 13.639px;
  fill: var(--svg-color--c1694f, #c1694f);
  rx: 3.679px;
  ry: 1.84px;
}

.rinl4yb3v {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M11.642 16.734c-1.569-.516-3.352-.369-4.108.339c-.005.04-.024.078-.024.118c0 1.016 1.647 1.84 3.679 1.84c1.063 0 2.013-.229 2.684-.589c-.333-.692-1.086-1.332-2.231-1.708");
}

.v9wqvwzzb {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M18.453 13.182c-1.569-.516-3.352-.369-4.108.339c-.005.04-.024.078-.024.118c0 1.016 1.647 1.84 3.679 1.84c1.063 0 2.013-.229 2.684-.589c-.333-.692-1.086-1.332-2.231-1.708");
}

.vmey65b6d {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M22.224 4.682c1.076-.558 1.113-.628 2.249-.024s9.846 5.248 10.487 5.589c.814.434 1.112.591-.449 1.421c-1.696.902-20.306 10.763-20.932 11.074c-.765.381-1.311.327-2.206-.112c-.718-.352-9.826-5.226-10.553-5.639c-.82-.465-.482-.706.769-1.37z");
}

.we_us-b9i {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M.373 16.56v9.722h.004c-.012.149.129.295.443.473c.727.412 9.835 5.286 10.553 5.639c.432.212.781.329 1.114.356V16.56z");
}

.zh3rdqbio {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M25.264 9.63c-1.569-.516-3.352-.369-4.108.339c-.005.04-.024.078-.024.118c0 1.016 1.647 1.84 3.679 1.84c1.063 0 2.012-.229 2.684-.589c-.333-.692-1.086-1.332-2.231-1.708");
}

</style>
