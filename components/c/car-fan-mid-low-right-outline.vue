<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo62bac_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-mid-low-right-outline" /></template>
<style>
.wo62bac_g {
  fill: currentColor;
  d: path("m9.802 22l-.86-.52l3.239-5.076q.217-.302.507-.478t.627-.176h3.627l1.624-5.64q.192-.645.636-1.031q.444-.387 1.006-.387q.777 0 1.28.595t.354 1.372L20.691 16.4q-.106.585-.553.939q-.448.353-1.019.353h-6.321zM20.519 7.692q-.613 0-1.037-.424t-.424-1.037t.424-1.038t1.037-.424t1.038.424t.424 1.038t-.424 1.037t-1.038.424m-9.23 2.212l-.708-.708l2.902-2.946H7.019v-.98h6.483l-2.94-2.941l.727-.675l4.115 4.115zm-5.173 8.48L2 14.27l.733-.688l2.902 2.921L5.615 10h1v6.502l2.908-2.883l.727.65z");
}

</style>
