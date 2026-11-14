<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wshrknbvf"/><path class="zxvr0--dp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fabric-softener" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wshrknbvf {
  d: path("M12.019 21.5H6.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4 19v-8q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277q.057-.136.126-.266q.07-.13.152-.253q.081-.122.175-.236t.198-.218q.104-.105.218-.198t.236-.175q.123-.082.253-.152t.266-.126t.277-.099t.286-.071t.291-.044T7 8h6q.147 0 .294.014t.291.044q.145.028.286.071t.277.099t.266.126t.253.152q.122.081.236.175t.218.198q.105.104.198.218t.175.236t.152.253t.126.266t.099.277t.071.286t.044.291Q16 10.853 16 11v2.508");
}

.zxvr0--dp {
  d: path("M12.5 8V4.5h-5V8m0-3.5L5.25 2.75m11 18.25a2 2 0 0 1-.25-4a2.5 2.5 0 0 1 4.25.25A1.75 1.75 0 0 1 20 21Z");
}

</style>
