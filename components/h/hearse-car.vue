<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2v5m6m8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hearse-car" /></template>
<style>
.x2v5m6m8p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6.5v9q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.438q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h5.876q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V11q0-2.25-2.25-2.25h-2.133l-3.275-4.21q-.053-.068-.119-.122q-.067-.054-.143-.092q-.077-.037-.161-.057q-.083-.019-.169-.019H4q-2.25 0-2.25 2.25M7 7.25h3q2.25 0 2.25 2.25T10 11.75H7q-2.25 0-2.25-2.25T7 7.25");
}

</style>
