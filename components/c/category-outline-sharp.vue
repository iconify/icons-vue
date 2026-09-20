<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta9pkabxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:category-outline-sharp" /></template>
<style>
.ta9pkabxh {
  fill: currentColor;
  d: path("M7.885 10.23L12 3.463l4.116 6.769zm9.615 11q-1.567 0-2.649-1.081T13.769 17.5t1.082-2.649t2.649-1.082t2.649 1.082t1.082 2.649t-1.082 2.649t-2.649 1.082m-13.73-.5v-6.462h6.46v6.462zm13.73-.5q1.146 0 1.939-.792t.792-1.939t-.792-1.939t-1.939-.792t-1.939.792t-.792 1.939t.792 1.939t1.939.792m-12.73-.5h4.46v-4.462H4.77zm4.857-10.5h4.746L12 5.427zM17.5 17.5");
}

</style>
