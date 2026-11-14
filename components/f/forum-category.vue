<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm2f15brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:forum-category" /></template>
<style>
.dm2f15brt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5.5q0-1.139.805-1.945Q3.861 2.75 5 2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v5.257q-.621-.257-1.5-.257h-5q-3 0-3 3v2.75H5q-2.75 0-2.75-2.75zm11.25 10q0-1.75 1.75-1.75h5q1.75 0 1.75 1.75V19q0 1.75-1.75 1.75H17.5l-1.8 1.35q-.059.044-.126.076q-.066.032-.138.051q-.071.018-.145.022t-.147-.007t-.143-.034q-.07-.025-.133-.063q-.064-.037-.119-.087t-.099-.108q-.073-.097-.112-.213q-.038-.115-.038-.237v-.854q-1-.323-1-1.646zm3.3 3.9l-.8.6q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.25 0-.25-.25v-3.5q0-.25.25-.25h5q.25 0 .25.25V19q0 .25-.25.25h-3q-.122 0-.237.038q-.116.039-.213.112m.45-1.4q-.254 0-.5.064q-.246.063-.468.186h-.032V16.5h3V18z");
}

</style>
