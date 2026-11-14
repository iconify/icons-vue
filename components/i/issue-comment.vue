<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gdjknqbvl"/><path class="o_ql9wbxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:issue-comment" /></template>
<style>
.gdjknqbvl {
  d: path("M10.5 19a8.5 8.5 0 1 1 8.5-8.5");
}

.o_ql9wbxa {
  d: path("M12.582 11.885q.204-.308.311-.662Q13 10.87 13 10.5q0-.123-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231q-.047-.113-.105-.221q-.058-.109-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165t-.197-.146t-.211-.126t-.221-.105q-.114-.047-.231-.082t-.238-.06q-.121-.024-.243-.036T10.5 8t-.245.012t-.243.036q-.12.024-.238.06t-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238q-.024.121-.036.243T8 10.5t.012.245t.036.243q.024.12.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126t.221.105q.114.047.231.082t.238.06q.121.024.243.036T10.5 13q.213 0 .424-.036q.21-.036.411-.108q.202-.071.388-.175q.186-.105.352-.239M14 15a1.5 1.5 0 0 1 1.5-1.5h5A1.5 1.5 0 0 1 22 15v3a1.5 1.5 0 0 1-1.5 1.5h-3l-2 1.5v-1.5A1.5 1.5 0 0 1 14 18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
