<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp1bk8h2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gdpr-shield" /></template>
<style>
.jp1bk8h2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.279 1.804l7.5 3q.104.041.191.112q.088.07.151.164q.063.093.096.2t.033.22V11q0 7.447-7.931 11.179q-.151.071-.319.071t-.319-.071Q3.75 18.447 3.75 11V5.5q0-.112.033-.22q.033-.107.096-.2t.151-.164q.087-.071.191-.112l7.5-3q.135-.054.279-.054t.279.054M11 10.25h2V9.5q0-.414-.293-.707T12 8.5q-1 0-1 1zm3.5.328V9.5q0-1.036-.732-1.768T12 7Q9.5 7 9.5 9.5v.964q-1.25.518-1.25 2.286v1.5q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768q-.243-.242-.518-.404");
}

</style>
