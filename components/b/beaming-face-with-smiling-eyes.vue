<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="f7hltwb1r"/><path class="k5tpdk7bb"/><g class="stn50abee"><path class="mrq_ibbau"/><path class="ks31dqsfi"/></g><path class="y-zdc-bym"/><path class="oeth_7bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:beaming-face-with-smiling-eyes" /></template>
<style>
.f7hltwb1r {
  cx: 32px;
  cy: 32px;
  r: 32px;
  fill: var(--svg-color--fbbf67, #fbbf67);
}

.k5tpdk7bb {
  fill: var(--svg-color--fff, #fff);
  d: path("M54 47.5c0 4.143-3.478 7.5-7.768 7.5H18.268c-4.29 0-7.768-3.357-7.768-7.5s3.478-7.5 7.768-7.5h27.965C50.522 40 54 43.357 54 47.5");
}

.ks31dqsfi {
  d: path("M19 38h2v17h-2zm8 0h2v17h-2zm9 0h2v17h-2zm8 0h2v17h-2z");
}

.mrq_ibbau {
  d: path("M10 46h44v2H10z");
}

.oeth_7bfz {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M29.451 26.994c-1.641-4.479-5.359-8.765-10.497-8.664c-4.792.092-7.679 5.16-9.24 8.999c-.975 2.396 2.905 3.427 3.866 1.065c1.01-2.465 2.482-5.184 5.19-6.01c3.104-.946 5.948 3.314 6.814 5.681c.883 2.405 4.758 1.366 3.867-1.068m6.97-.046c1.638-4.479 5.358-8.766 10.496-8.666c4.792.092 7.679 5.161 9.241 8.998c.974 2.396-2.907 3.43-3.869 1.066c-1-2.464-2.481-5.185-5.189-6.01c-3.104-.949-5.949 3.312-6.815 5.678c-.881 2.408-4.757 1.367-3.864-1.065");
}

.stn50abee {
  fill: var(--svg-color--ccc, #ccc);
}

.y-zdc-bym {
  fill: var(--svg-color--a5692d, #a5692d);
  d: path("M46.23 56H18.266c-5.111 0-9.268-4.04-9.268-9s4.157-9 9.268-9h27.965c5.11 0 9.268 4.04 9.268 9s-4.158 9-9.269 9M18.266 41c-3.456 0-6.268 2.691-6.268 6s2.812 6 6.268 6h27.965c3.456 0 6.268-2.691 6.268-6s-2.812-6-6.268-6z");
}

</style>
