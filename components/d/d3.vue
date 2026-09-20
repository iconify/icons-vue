<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":243};
const content = `<defs><linearGradient id="SVG7SWXidyE" x1="-82.637%" x2="103.767%" y1="-92.82%" y2="106.042%"><stop offset="0%" class="xd2u_yb6m"/><stop offset="100%" class="wspxeq7th"/></linearGradient><linearGradient id="SVG0SgAgcVm" x1="-258.924%" x2="97.62%" y1="-248.97%" y2="98.768%"><stop offset="0%" class="xd2u_yb6m"/><stop offset="100%" class="wspxeq7th"/></linearGradient><linearGradient id="SVGd3xP6bjI" x1="-223.163%" x2="94.028%" y1="-261.968%" y2="101.691%"><stop offset="0%" class="xd2u_yb6m"/><stop offset="100%" class="wspxeq7th"/></linearGradient><linearGradient id="SVGvjHJFcJx" x1="11.339%" x2="82.496%" y1="-1.822%" y2="92.107%"><stop offset="0%" class="yoj3dhczp"/><stop offset="100%" class="xd2u_yb6m"/></linearGradient><linearGradient id="SVGVtWIye7c" x1="15.844%" x2="120.126%" y1="3.858%" y2="72.38%"><stop offset="0%" class="d-ooxsbah"/><stop offset="100%" class="gnnhq8b5q"/></linearGradient><linearGradient id="SVGXrBHqbTI" x1="46.984%" x2="51.881%" y1="23.466%" y2="147.391%"><stop offset="0%" class="xd2u_yb6m"/><stop offset="100%" class="wspxeq7th"/></linearGradient></defs><path fill="url(#SVG7SWXidyE)" class="qjlg9ca-k"/><path fill="url(#SVG0SgAgcVm)" class="mwpmpmbkk"/><path fill="url(#SVGd3xP6bjI)" class="zrfx8eboc"/><path fill="url(#SVGvjHJFcJx)" class="mj80lwb8f"/><path fill="url(#SVGVtWIye7c)" class="yx-wpibkd"/><path fill="url(#SVGXrBHqbTI)" class="ks9sw78zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:d3" /></template>
<style>
.d-ooxsbah {
  stop-color: var(--svg-color--b84e51, #b84e51);
}

.gnnhq8b5q {
  stop-color: var(--svg-color--f68e48, #f68e48);
}

.ks9sw78zy {
  d: path("M176.765 242.016H95.808c16.296-10.064 30.384-23.35 41.443-38.928zm-54.453-53.645l-39.16-38.59c-10.819 23.251-34.395 39.422-61.685 39.422H0v53.208h21.467c42.01 0 79.09-21.488 100.845-54.04");
}

.mj80lwb8f {
  d: path("M255.835 171.568c-1.766 39.147-34.152 70.448-73.72 70.448h-5.35l-39.514-38.928c3.25-4.584 6.272-9.333 8.962-14.285h35.902c11.354 0 20.594-9.235 20.594-20.595c0-11.355-9.24-20.595-20.594-20.595h-21.246c1.619-8.557 2.504-17.381 2.504-26.408c0-9.165-.901-18.114-2.578-26.808h13.197l81.61 80.414c.097-1.078.174-2.155.233-3.243M21.467 0H0v53.213h21.467c37.493 0 68 30.499 68 67.992c0 10.2-2.275 19.883-6.318 28.576l39.163 38.59c12.859-19.24 20.376-42.339 20.376-67.166C142.688 54.373 88.307 0 21.467 0");
}

.mwpmpmbkk {
  d: path("M83.472 149.077q-.16.353-.323.704q-.172.37-.349.734c-2.57 5.36 35.987 43.053 39.088 38.474c.141-.202.283-.416.424-.618c.157-.24.312-.47.467-.71c2.48-3.765-38.206-41.032-39.307-38.584");
}

.qjlg9ca-k {
  d: path("M255.52 175.619c.115-1.115.197-2.24.261-3.371c.078-1.339-80.562-77.85-80.562-77.85h-1.928s81.736 86.215 82.229 81.22");
}

.wspxeq7th {
  stop-color: var(--svg-color--f7974e, #f7974e);
}

.xd2u_yb6m {
  stop-color: var(--svg-color--f9a03c, #f9a03c);
}

.yoj3dhczp {
  stop-color: var(--svg-color--f26d58, #f26d58);
}

.yx-wpibkd {
  d: path("M182.115 0H95.187C116.419 12.963 134 31.344 145.979 53.213h36.136c11.354 0 20.594 9.235 20.594 20.595c0 11.357-9.24 20.592-20.594 20.592h-8.12l81.61 80.413c.192-2.181.312-4.376.312-6.605c0-17.939-6.437-34.395-17.125-47.203c10.688-12.802 17.125-29.261 17.125-47.197C255.917 33.112 222.813 0 182.115 0");
}

.zrfx8eboc {
  d: path("M137.957 202.083c-.109.24-.885 1.552-1.594 2.245c-.12.24 37.64 37.688 37.64 37.688h3.4c.002 0-35.446-38.35-39.446-39.933");
}

</style>
