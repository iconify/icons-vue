<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n38o7cc2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-check" /></template>
<style>
.n38o7cc2i {
  fill: currentColor;
  d: path("M15.3 10.077L18.671 6.7l-.546-.546L15.3 8.979l-1.425-1.406l-.546.552zM4 19.5v-1h11v1zm8.818-8.318Q11.5 9.864 11.5 8t1.318-3.182T16 3.5t3.182 1.318T20.5 8t-1.318 3.182T16 12.5t-3.182-1.318M4 11.5v-1h5.377q.098.28.217.521q.12.24.272.479zm0 4v-1h9.266q.401.177.84.309t.894.193v.498z");
}

</style>
