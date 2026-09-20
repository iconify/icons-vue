<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="r4qc_abod"><path class="h0dqwzvmd"/><path class="i_anfsynt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kukai" /></template>
<style>
.h0dqwzvmd {
  d: path("M12 7.67a4.33 4.33 0 1 0 0 8.66a4.33 4.33 0 0 0 0-8.66m0 6.3a1.97 1.97 0 1 1 0-3.94a1.97 1.97 0 0 1 0 3.94");
}

.i_anfsynt {
  d: path("M17.4 3H6.6A3.6 3.6 0 0 0 3 6.6v10.8A3.6 3.6 0 0 0 6.6 21h10.8a3.6 3.6 0 0 0 3.6-3.6V6.6A3.6 3.6 0 0 0 17.4 3m.406 12.18q.072.052.136.117a1.183 1.183 0 0 1-1.585 1.756l-.037-.031a.385.385 0 0 0-.49-.02A6.27 6.27 0 0 1 12 18.3a6.27 6.27 0 0 1-3.83-1.297a.385.385 0 0 0-.49.019l-.037.03a1.185 1.185 0 1 1-1.449-1.873a.38.38 0 0 0 .118-.467A6.3 6.3 0 0 1 5.7 12c0-.97.22-1.89.612-2.712a.38.38 0 0 0-.123-.47l-.038-.03a1.184 1.184 0 1 1 1.532-1.806a.38.38 0 0 0 .486.015a6.27 6.27 0 0 1 3.83-1.297a6.28 6.28 0 0 1 3.83 1.297a.385.385 0 0 0 .49-.019l.037-.03a1.185 1.185 0 1 1 1.448 1.873a.38.38 0 0 0-.117.467c.392.822.612 1.741.612 2.712c0 .97-.22 1.89-.612 2.712a.38.38 0 0 0 .119.467");
}

.r4qc_abod {
  fill: var(--svg-color--5963ff, #5963ff);
  fill-rule: evenodd;
}

</style>
