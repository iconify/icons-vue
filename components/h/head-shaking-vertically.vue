<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="j4d0y110o"/><path class="sd5w7o5jo"/><path class="vyf56obse"/><path class="co_7dtomw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:head-shaking-vertically" /></template>
<style>
.co_7dtomw {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M9.578 12.63c-.48 0-.91-.35-.99-.84c-.61-3.83.78-6.84 2.05-8.69c.31-.45.94-.57 1.39-.26c.46.31.57.94.26 1.39c-1.55 2.25-2.13 4.69-1.73 7.24a.99.99 0 0 1-.83 1.14c-.04.02-.09.02-.15.02");
}

.j4d0y110o {
  cx: 18px;
  cy: 20px;
  r: 16px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.sd5w7o5jo {
  fill: var(--svg-color--664500, #664500);
  d: path("M27.85 22.97a.52.52 0 0 0-.54-.01c-.01.01-1.12.66-3.29.66s-3.28-.65-3.28-.66c-.16-.1-.39-.1-.54.01c-.16.1-.21.28-.13.43c.05.1 1.33 2.4 3.96 2.4s3.9-2.3 3.96-2.4c.07-.15.01-.33-.14-.43m-12.58-.01c-.01.01-1.12.66-3.29.66s-3.28-.65-3.28-.66c-.16-.1-.39-.1-.54.01c-.16.1-.22.28-.14.43c.05.1 1.33 2.4 3.96 2.4s3.9-2.3 3.96-2.4c.08-.15.03-.33-.13-.43a.52.52 0 0 0-.54-.01m-2.87 6.57c.03.14.89 3.33 5.69 3.33c4.81 0 5.66-3.19 5.69-3.33a.37.37 0 0 0-.18-.42a.395.395 0 0 0-.46.06c-.01.01-1.49 1.41-5.06 1.41s-5.04-1.4-5.06-1.41a.39.39 0 0 0-.46-.06c-.13.08-.2.25-.16.42");
}

.vyf56obse {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M6.61 15.95c-.41 0-.79-.25-.94-.66C2.56 6.74 8.36.63 8.61.37C9-.02 9.63-.03 10.03.35s.41 1.02.02 1.41c-.21.23-5.17 5.5-2.5 12.84a1 1 0 0 1-.6 1.28c-.11.05-.22.07-.34.07");
}

</style>
