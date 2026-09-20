<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGe2Dq1sES" cx="20.365" cy="6.269" r="2.721" gradientTransform="matrix(-.148 .989 1.059 .158 11.812 -5.692)" gradientUnits="userSpaceOnUse"><stop offset="0" class="u-g7kcrga"/><stop offset=".5" class="if4itl3ut"/><stop offset="1" class="a16vb7bpj"/></radialGradient><radialGradient id="SVGFdebDgyO" cx="6.566" cy="14.644" r="3.9" gradientTransform="matrix(-.148 .989 1.059 .158 9.451 15.181)" href="#SVGe2Dq1sES"/></defs><path class="hq48v6w8x"/><path class="h28h8eflo"/><path class="ugq5_7bab"/><path class="eltks6b4k"/><path fill="url(#SVGe2Dq1sES)" class="kujt23p-e"/><path class="oz0jmrb7m"/><path class="t9avry21f"/><path class="umari2ngb"/><path class="c8xikbb3h"/><path fill="url(#SVGFdebDgyO)" class="fpq_7dbct"/><path class="ckk2k_87z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-services-opened" /></template>
<style>
.a16vb7bpj {
  stop-color: var(--svg-color--404f5c, #404f5c);
  stop-opacity: 0.84;
}

.c8xikbb3h {
  fill: var(--svg-color--a9a9a9, #a9a9a9);
  d: path("M24.081 29.045a5.053 5.053 0 1 0-5.14-4.964a5.054 5.054 0 0 0 5.14 4.964m-.163-9.327a4.275 4.275 0 1 1-4.2 4.35a4.275 4.275 0 0 1 4.2-4.35");
}

.ckk2k_87z {
  fill: var(--svg-color--a9a9a9, #a9a9a9);
  d: path("M24.033 26.324a2.331 2.331 0 1 0-2.372-2.291a2.33 2.33 0 0 0 2.372 2.291m-.075-4.3a1.973 1.973 0 1 1-1.938 2.007a1.97 1.97 0 0 1 1.938-2.007");
}

.eltks6b4k {
  fill: var(--svg-color--a9a9a9, #a9a9a9);
  d: path("M15.5 18.939a3.5 3.5 0 1 0-3.555-3.439a3.5 3.5 0 0 0 3.555 3.439m-.113-6.457a2.96 2.96 0 1 1-2.907 3.012a2.96 2.96 0 0 1 2.91-3.012Z");
}

.fpq_7dbct {
  d: path("M24.061 27.893a3.9 3.9 0 1 0-3.967-3.832a3.9 3.9 0 0 0 3.967 3.832m-.105-6.027a2.128 2.128 0 1 1-2.09 2.164a2.127 2.127 0 0 1 2.089-2.164Z");
}

.h28h8eflo {
  fill: var(--svg-color--silver, silver);
  d: path("m13.886 12.006l-1.803 1.803l-.901-1.803l.901-.901zm2.886-.094h-2.551L14.859 10h1.274zm2.105 1.974l-1.803-1.803l1.803-.901l.902.901zm.094 2.886v-2.551l1.912.638v1.274zm-1.974 2.105l1.803-1.803l.901 1.803l-.901.902zm-2.885.094h2.55l-.637 1.912H14.75zm-2.106-1.974l1.803 1.803l-1.803.901l-.901-.901zm-.094-2.885v2.55L10 16.025V14.75z");
}

.hq48v6w8x {
  fill: var(--svg-color--7bbedb, #7bbedb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.if4itl3ut {
  stop-color: var(--svg-color--8e9e9e, #8e9e9e);
  stop-opacity: 0.74;
}

.kujt23p-e {
  d: path("M15.489 18.162a2.721 2.721 0 1 0-2.767-2.673a2.72 2.72 0 0 0 2.767 2.673m-.075-4.275a1.555 1.555 0 1 1-1.528 1.583a1.555 1.555 0 0 1 1.528-1.583");
}

.oz0jmrb7m {
  fill: var(--svg-color--a9a9a9, #a9a9a9);
  d: path("M15.47 17a1.555 1.555 0 1 0-1.583-1.526A1.555 1.555 0 0 0 15.47 17m-.051-2.87a1.316 1.316 0 1 1-1.292 1.339a1.316 1.316 0 0 1 1.292-1.337Z");
}

.t9avry21f {
  fill: var(--svg-color--silver, silver);
  d: path("m27.572 19.763l-1.706-.947l1.098-1.176l1.024.568zm1.636 2.356l-1.005-1.672l1.539-.47l.603 1.004zm.238 2.859l-.034-1.951l1.568.363l.02 1.17zm-1.223 2.594l.946-1.706l1.176 1.098l-.567 1.024zm-2.357 1.636l1.673-1.005l.469 1.539l-1.003.603zm-2.859.238l1.952-.034l-.363 1.568l-1.171.02zm-2.594-1.223l1.706.946l-1.098 1.176l-1.024-.567zm-1.636-2.357l1.005 1.673l-1.539.469l-.603-1.003zm-.238-2.859l.034 1.952l-1.567-.363l-.021-1.171zm1.224-2.594l-.947 1.706l-1.176-1.098l.568-1.024zm2.356-1.636l-1.672 1.005l-.47-1.539l1.004-.603zm2.859-.238l-1.951.034l.363-1.567l1.17-.021z");
}

.u-g7kcrga {
  stop-color: var(--svg-color--bedcdc, #bedcdc);
}

.ugq5_7bab {
  fill: var(--svg-color--silver, silver);
  d: path("M11.663 15.442a3.778 3.778 0 1 1 1.107 2.672a3.78 3.78 0 0 1-1.107-2.672m3.779 1.425a1.425 1.425 0 1 0-1.008-.418a1.43 1.43 0 0 0 1.008.418");
}

.umari2ngb {
  fill: var(--svg-color--silver, silver);
  d: path("M23.9 18.372a5.626 5.626 0 1 1-3.946 1.716a5.63 5.63 0 0 1 3.946-1.716m-2.017 5.658a2.112 2.112 0 1 0 .592-1.5a2.1 2.1 0 0 0-.592 1.5");
}

</style>
