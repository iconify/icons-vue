<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkacm6b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:line-symmetry" /></template>
<style>
.bkacm6b4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 2.5v19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-19q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146m4.736 6.226q1.085-.985 2.424-.393q1.34.593 1.34 2.058v3.218q0 1.465-1.34 2.058q-1.339.592-2.423-.393l-1.77-1.609q-.737-.67-.737-1.665t.737-1.665zm-9.203 1.609l-1.77-1.609q-1.084-.985-2.423-.393q-1.34.593-1.34 2.058v3.218q0 1.465 1.34 2.058q1.339.592 2.423-.393l1.77-1.609q.737-.67.737-1.665t-.737-1.665");
}

</style>
