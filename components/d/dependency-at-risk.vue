<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngj7i4bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dependency-at-risk" /></template>
<style>
.ngj7i4bbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm16.774 2.899q.118-.032.234-.073q.116-.042.228-.092q.112-.051.219-.111q.108-.059.21-.127q.102-.069.198-.145t.186-.16t.173-.175t.157-.189q.075-.097.142-.2t.124-.212q.058-.108.107-.221t.089-.229t.069-.236t.05-.24q.02-.121.03-.244q.01-.122.01-.245q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277q-.057-.136-.126-.266q-.07-.13-.152-.253q-.081-.122-.175-.236t-.198-.218t-.218-.198t-.236-.175q-.123-.082-.253-.152t-.266-.126t-.277-.099t-.286-.071q-.144-.029-.291-.044T18.5 4.5t-.294.014q-.147.015-.291.044q-.145.028-.286.071t-.277.099q-.136.057-.266.126q-.13.07-.253.152q-.122.081-.236.175t-.218.198t-.198.218t-.175.236q-.082.123-.152.253t-.126.266t-.099.277t-.071.286t-.044.291t-.014.294q0 .188.024.375q.023.187.07.369q.046.182.115.357q.07.175.16.34t.201.318q.11.152.239.29q.128.137.273.258q.145.12.303.221M8.5 7.5h2m3 0h2M18 14l3.5 6.75h-7Zm0 4.25h.01");
}

</style>
