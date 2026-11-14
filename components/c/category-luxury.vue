<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4t-z2bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-luxury" /></template>
<style>
.i4t-z2bvn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.748 9.439l.721.64q.345.307.801.244q.456-.062.705-.45l1.922-2.99Q10.635 5.736 12 5.736t2.103 1.148l1.922 2.99q.249.388.705.45q.456.063.801-.243l.721-.642q.952-.847 2.064-.222t.883 1.88l-1.2 6.6q-.373 2.053-2.46 2.053H6.461q-2.087 0-2.46-2.053l-1.2-6.601q-.229-1.254.883-1.879q1.111-.625 2.064.222");
}

</style>
