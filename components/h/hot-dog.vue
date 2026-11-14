<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp_r2xwlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hot-dog" /></template>
<style>
.wp_r2xwlp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.826 5.139l-10.24 7.17q-3.276 2.294-.982 5.57l.089.126q-.413-.647-.278-1.415q.144-.816.823-1.291l13.516-9.464q.678-.476 1.494-.332q.776.137 1.244.758l-.096-.14q-2.294-3.276-5.57-.982m5.866 1.439q.296.575.179 1.242q-.144.816-.823 1.291L6.532 18.575q-.678.476-1.494.332q-.66-.117-1.097-.582q2.194 2.664 5.233.536l10.24-7.17q3.045-2.132 1.278-5.113");
}

</style>
