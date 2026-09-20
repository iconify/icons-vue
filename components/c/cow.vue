<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t3do0rbol"/><path class="lvif9_wyh"/><circle class="rfu82bcit"/><circle class="rcjzf1bqy"/><path class="jqg55w0jc"/><circle class="urkbt6dos"/><path class="ld7od2boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cow" /></template>
<style>
.jqg55w0jc {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M11 9c0 .552-.671 1-1.5 1S5 7.552 5 7s2.23-.308 3 0c2.5 1 3 1.448 3 2");
}

.ld7od2boe {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M35 24a1 1 0 0 1-1-1v-5c0-1.44-.561-2-2-2a1 1 0 1 1 0-2c2.542 0 4 1.458 4 4v5a1 1 0 0 1-1 1");
}

.lvif9_wyh {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M10 22c-2 0-4.946.087-6.973.087S-.617 18.609.692 17.305C2 16 6 15 5 11c-.542-2.169 4-3 6-2c4.816 2.408 5 10-2 10c0 0 3 3 1 3m20-11c-2.586.97-5.485 1.101-8.226.838A8.3 8.3 0 0 0 20 17c0 4.418 3.357 8 7.5 8c2.587 0 4.866-1.396 6.215-3.521c.181-1.872.285-4.017.285-6.479c0-2-2.127-4.702-4-4");
}

.rcjzf1bqy {
  cx: 30px;
  cy: 28px;
  r: 2px;
  fill: var(--svg-color--31373d, #31373d);
}

.rfu82bcit {
  cx: 17.5px;
  cy: 24.5px;
  r: 3.5px;
  fill: var(--svg-color--31373d, #31373d);
}

.t3do0rbol {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M34 15c0-2-2.127-4.702-4-4c-8 3-19-2-19-2c-2.209 0-6.857 9.257-5 10q.414.168.799.343C4.648 20.087 4.283 21.809 6 22c9 1 6.896 14 8 14c1.344 0 2.685-2.614 3.422-5h9.8c.288 2.354.866 5 1.778 5c.866 0 2.611-3.542 3.794-9.142C33.528 24.232 34 20.326 34 15");
}

.urkbt6dos {
  cx: 8px;
  cy: 13px;
  r: 1px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

</style>
