<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu7op7b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:linked-camera-outline-sharp" /></template>
<style>
.mu7op7b1m {
  fill: currentColor;
  d: path("M20.15 7.462q0-1.931-1.339-3.271q-1.339-1.341-3.273-1.341V2q2.27 0 3.866 1.593T21 7.462zm-2.65 0q0-.806-.576-1.384T15.538 5.5v-.85q1.183 0 1.992.812q.808.811.82 2zM3 20V6h4.573l1.85-2h5.116v1H9.856L8.012 7H4v12h16V8.462h1V20zm9-3.27q1.567 0 2.649-1.081T15.731 13t-1.082-2.649T12 9.269t-2.649 1.082T8.269 13t1.082 2.649T12 16.731m0-1q-1.165 0-1.948-.783T9.269 13t.783-1.948T12 10.269t1.948.783t.783 1.948t-.783 1.948t-1.948.783");
}

</style>
