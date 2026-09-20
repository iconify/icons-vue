<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w_d9z5bti"/><path class="yz174gbcg"/><path class="s92u30b_b"/><path class="xk13p9ssx"/><path class="awnn019zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:incoming-envelope" /></template>
<style>
.awnn019zm {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M32.832 9h-20c-1.578 0-3.189.921-4.217 2.248l9.217 8.794c.749.719 2.434.729 3.656 0l14.294-8.768C35.516 9.933 34.42 9 32.832 9");
}

.s92u30b_b {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M17.336 17.636L4.384 26.949c-.034.028-.054.063-.085.091a2.66 2.66 0 0 0 .992 1.384c.035-.023.073-.033.107-.06L18.35 19.05c.501-.391.681-1.023.401-1.414c-.281-.391-.913-.391-1.415 0m13.81 9.404c-.015-.028-.016-.063-.034-.09l-7.674-9.314c-.281-.391-.913-.391-1.416 0c-.501.391-.68 1.023-.4 1.414l7.676 9.314c.018.026.051.037.072.06a6 6 0 0 0 1.776-1.384");
}

.w_d9z5bti {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M7 12a1 1 0 0 1-1 1H1a1 1 0 0 1 0-2h5a1 1 0 0 1 1 1m-2 5a1 1 0 0 1-1 1H1a1 1 0 0 1 0-2h3a1 1 0 0 1 1 1m-2 5a1 1 0 0 1-1 1H1a1 1 0 1 1 0-2h1a1 1 0 0 1 1 1");
}

.xk13p9ssx {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M35.699 13c.626-2.209-.658-4-2.867-4h-20c-2.209 0-4.507 1.791-5.133 4l-.021.074l8.806 8.452c1.631 1.584 3.788 1.475 5.725.371l13.227-7.964z");
}

.yz174gbcg {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M32.301 25c-.626 2.209-2.925 4-5.134 4h-20c-2.209 0-3.492-1.791-2.866-4l3.398-12c.626-2.209 2.924-4 5.133-4h20c2.209 0 3.493 1.791 2.867 4z");
}

</style>
